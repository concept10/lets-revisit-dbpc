DBPC Tags : interfaces and methods description

DBPC

    DBPC Tags : interfaces and methods description

Introduction

All data points available trough DBPC are represented by an tags object. Those objects are available trough DBUS thanks to a DBPC server.

This part describe standard DBPC tags class models.

There is a basic class called tag. all tags class corresponding to data points value are inherited from this basic class
Tags interface

  <interface name="org.dbpc.tag">
    <method name="get_description">
      <arg direction="out" type="s" />
    </method>
    <method name="get_refresh">
      <arg direction="out" type="s" />
    </method>
    <method name="get_validity">
      <arg direction="out" type="s" />
    </method>
    <method name="get_device">
      <arg direction="out" type="s" />
    </method>
    <method name="get_adress">
      <arg direction="out" type="s" />
    </method>
    <method name="get_name">
      <arg direction="out" type="s" />
    </method>
  </interface>

Boolean interface

  <interface name="org.dbpc.boolean">
    <method name="read">
      <arg direction="out" type="b" />
    </method>
    <method name="write">
      <arg direction="in"  type="b" name="value" />
      <arg direction="out" type="b" />
    </method>
  </interface>

Interger interface

  <interface name="org.dbpc.integer">
    <method name="read">
      <arg direction="out" type="i" />
    </method>
    <method name="write">
      <arg direction="in"  type="i" name="value" />
      <arg direction="out" type="b" />
    </method>
  </interface>

Real interface

...
Analog input interface

...
Analog output interface

...
Alarm Interface interface

...
Isa88 Function interface

...
Links: DBPC
Last edited Sat 18 May 2013 07:50:35 AM UTC