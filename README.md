# B2_Reseau_TP4

[config infra](https://github.com/akhadimer/B2_Reseau_TP4/blob/master/infra-sw1.conf)

[config sw1](https://github.com/akhadimer/B2_Reseau_TP4/blob/master/client-sw1.conf)

[config sw2](https://github.com/akhadimer/B2_Reseau_TP4/blob/master/client-sw2.conf)

[config sw3](https://github.com/akhadimer/B2_Reseau_TP4/blob/master/client-sw3.conf)

[config r1](https://github.com/akhadimer/B2_Reseau_TP4/blob/master/r1.conf)

Ping :
- admin 1 vers admin 3 :

```
admin1> ping 10.5.10.13
84 bytes from 10.5.10.13 icmp_seq=1 ttl=64 time=0.466 ms
84 bytes from 10.5.10.13 icmp_seq=2 ttl=64 time=0.902 ms
84 bytes from 10.5.10.13 icmp_seq=3 ttl=64 time=0.683 ms
84 bytes from 10.5.10.13 icmp_seq=4 ttl=64 time=0.741 ms
84 bytes from 10.5.10.13 icmp_seq=5 ttl=64 time=0.745 ms
```

- guest1 vers admin 1:

```
guest1> ping 10.5.10.11
10.5.10.11 icmp_seq=1 timeout
10.5.10.11 icmp_seq=2 timeout
84 bytes from 10.5.10.11 icmp_seq=3 ttl=63 time=14.125 ms
84 bytes from 10.5.10.11 icmp_seq=4 ttl=63 time=14.231 ms
84 bytes from 10.5.10.11 icmp_seq=5 ttl=63 time=20.486 ms
```
