# Task 3 WebSec

## Cyber Attack Map

![image](https://github.com/Khaders-sec/Task3-WebSec/assets/63330019/27902f3f-23bd-471d-aa01-513ad337451e)
A cyber attack map is a visual representation of real-time or historical cyber attacks on a geographic map. These maps show the type, location, and origin of the attacks, as well as the target and severity of the attacks.

One of the most well-known cyber attack maps is the ["Digital Attack Map"](https://www.digitalattackmap.com/) by Arbor Networks, which is a live visualization of global DDoS (Distributed Denial of Service) attacks. In this example, we will explain how DDoS attacks work and how the Digital Attack Map displays this information.

DDoS attacks overwhelm a server, network, or website with traffic from multiple sources, making it unavailable to users. The Digital Attack Map shows the top countries where attacks are originating from, the top targets of the attacks, and the top industries affected by the attacks. The map is updated in real-time, showing the frequency and intensity of attacks.

![image](https://github.com/Khaders-sec/Task3-WebSec/assets/63330019/f4fe7921-77a1-4d04-831a-e906b5e90f63)

On the map, we can see that the United States is both the top target of attacks and the top source of attacks. This is likely due to the high number of servers and websites hosted in the U.S., as well as the high number of devices that can be compromised and used as part of a botnet to launch attacks. We can also see that the financial and technology industries are the most targeted, likely due to the sensitive nature of their data and the potential financial gain for attackers.

The Digital Attack Map also includes a timeline view that shows the history of attacks over a period of time. This can be used to identify trends and patterns in the attacks and to track the effectiveness of mitigation strategies.

In summary, cyber attack maps provide a valuable tool for understanding the global landscape of cyber attacks and identifying potential threats. The Digital Attack Map is just one example of how this information can be displayed in a clear and easy-to-understand way.

### Additional Cyber Attack Maps

- [KasperSky Attack Map](https://cybermap.kaspersky.com/)
- [Horizon Attack Map](https://horizon.netscout.com/)
- [FortiNet Attack Map](https://threatmap.fortiguard.com/)
- [CheckPoint Attack Map](https://threatmap.checkpoint.com/)

## DDos Attack

For this attack we have used [MHDDoS](https://github.com/MatrixTM/MHDDoS) which is an opensource project that can be used for ddos attacks. It has many features! checkout thier docs.

![image](https://github.com/Khaders-sec/Task3-WebSec/assets/63330019/6e12f56a-965a-492a-b176-8e98e081ea60)

## Social Engineering
We have used [SET](https://github.com/trustedsec/social-engineer-toolkit)
![image](https://github.com/Khaders-sec/Task3-WebSec/assets/63330019/dd2d4a61-d95f-41e2-aca4-51a131eace85)
![image](https://github.com/Khaders-sec/Task3-WebSec/assets/63330019/90127535-b606-44a3-b9a1-0187afde2a22)

## Effects of syn flood
We have used [HAWK](https://github.com/medpaf/hawk)

![image](https://github.com/Khaders-sec/Task3-WebSec/assets/63330019/8fcf4781-5ecc-4310-a186-b36eb8560cb9)

We have noted these effects on the target:
- Slow response
- After a while the server totally crashed!
  * After restarting we found failures in some scheduled jobs
  * All cached data is lost
