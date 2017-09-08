# show ip ospf rib

## REST call

```



```

## REST response body

```
 


```


---

<pre>
R122#show ip ospf rib

            OSPF Router with ID (192.168.56.122) (Process ID 100)


		Base Topology (MTID 0)

OSPF local RIB
Codes: * - Best, > - Installed in global RIB

*   <b>6.6.6.6/32</b>, <b>Intra</b>, cost <b>1</b>, <b>area 20</b>, <b>Connected</b>
      via <b>6.6.6.6</b>, <b>Loopback1</b>
*>  7.7.7.7/32, Intra, cost 101, area 20
      via 8.8.8.1, GigabitEthernet3/0
*   <b>8.8.8.0/24</b>, <b>Intra</b>, cost <b>100</b>, <b>area 20</b>, <b>Connected</b>
      via <b>8.8.8.2</b>, <b>GigabitEthernet3/0</b>
*>  10.5.5.0/24, Intra, cost 101, area 20
      via 8.8.8.1, GigabitEthernet3/0
*   <b>10.7.7.0/24</b>, <b>Intra</b>, cost <b>1</b>, <b>area 20</b>, <b>Connected</b>
      via <b>10.7.7.1</b>, <b>GigabitEthernet1/0</b>
R122#
</pre>



