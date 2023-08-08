
DBPC Devices : specification, interfaces and methods description

DBPC

forthcoming ...
Interfaces

<!DOCTYPE node PUBLIC "-//freedesktop//DTD D-BUS Object Introspection 1.0//EN"
"http://www.freedesktop.org/standards/dbus/1.0/introspect.dtd">
<node name="/org/dbpc/device/FillingControler">

  <interface name="org.freedesktop.DBus.Introspectable">
    <method name="Introspect">
      <arg direction="out" type="s" />
    </method>
  </interface>

  <interface name="org.dbpc.device">
    <method name="get_server">
      <arg direction="out" type="s" />
    </method>
    <method name="disconnect">
      <arg direction="out" type="b" />
    </method>
    <method name="get_address">
      <arg direction="out" type="s" />
    </method>
    <method name="get_name">
      <arg direction="out" type="s" />
    </method>
    <method name="get_description">
      <arg direction="out" type="s" />
    </method>
    <method name="connect">
      <arg direction="out" type="b" />
    </method>
  </interface>

</node>

Links: DBPC
Last edited Sat 18 May 2013 07:50:35 AM UTC