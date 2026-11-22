# MISSION 7 - How computers communicate

## Task 7.1 - Explain network concepts

| Concept | Explain it in your own words | Example |
| --- | --- | --- |
| LAN | LAN stands for Local Area Network, and this type of network covers a small area. | This type of network is used in homes, labs and offices. |
| MAN | MAN stands for Metropolitan Area Network, and this type of network covers a large area expanding to a city. | This type of network is mainly used for cities or large campuses where the network is to be spread across a wide area. |
| WAN | WAN stands for Wide Area Network, and this type of network covers large geographical areas. | This type of network is used in large geographical areas such as states and sometimes even countries. |
| DNS | DNS stands for Domain Name System. Its main purpose is to convert the IP address of a website that is deployed on the internet to a human-readable domain. | For example it converts 192.168.12.2 into https://www.google.com/. |
| Router | Router is a networking device that is used to connect multiple networks and maintain and establish a smooth transfer of data between them. | Routers are installed in data centers where there are multiple data servers and a flow of data amongst them is required. |
| Protocol | Protocol can be defined as a certain set of instructions that are created for the devices to follow for an encrypted and efficient flow. | Protocols are set on certain networks such as college networks to maintain a proper etiquette within the campus. |
| Packet switching | This technology was developed as transferring large data at once was a huge hassle as it was quite possible that either the host or the recipient might lose the connection in between which might break the entire flow and corrupt the data that is being transferred. To overcome this issue, the large chunks of data are broken down into smaller packets which are then transferred. | We can see this happen in the background all the time when we download large files from the internet. |
| Client-server | This pipeline exists so as to make it easier to debug from which end the issue might be at. | Such a pipeline exists when we try to search anything on google, where thre user sends a search request and the servers go through their database and provides the relevant data for the same. |

---

## Task 7.2 - Observe network information

#### To check whether your computer can reach a public example website or not, we use the `curl` command followed by the -I attribute so as to send only an HTTP request and then the website URL as the arguement. We use the `nslookup` command, the DNS lookup tool, to find the network address associated with the example domain. The output for both the commands are present in the evidence folder.

#### A connectivity test helps you check if your device is connected to the network or not and helps you pinpoint where the flow of the connection is failing at.

#### The main information that is displayed when we use the DNS lookup tool is the mapping between the domain name and its network records, along with the DNS servers which answered the query that was sent by us.

#### When you enter a website name in a browser, the DNS(Domain Name System) translates the human-readable domain name into the numerical IP address of that particular website such that the browser will connect to the server of that IP on the internet to display the website.

---

## Task 7.3 - What happens when you open a website?

1. The user (client) will enter the human-readable website address (URL) into the browser. This process will signify that the **client** is requesting information.
2. The browser then sends a **query** from the local router to the **DNS** to translate the human-readable address to a numerical IP address.
3. Once the DNS sends the IP address to the computer and the computer receives it, the router will send a connection request on the internet, which will pass through multiple servers until it reaches its destination. 
4. When the connection request gets accepted, the browser connects to the target web server using standard internet protocols and requests for the website files in the form of data packets.
5. The data packets are the interpreted by the browser and then displayed on your screen.