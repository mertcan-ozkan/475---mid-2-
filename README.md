# 475---mid-2-
### 3 7 TCP Congestion Control den itiaren
- ![image](https://user-images.githubusercontent.com/74208991/208288750-eaffb844-a34b-4c23-9b61-3cd9f8009753.png)
- ![image](https://user-images.githubusercontent.com/74208991/208288787-54f0247c-532c-4dc7-a375-2da6ae950adb.png) 
- ![image](https://user-images.githubusercontent.com/74208991/208288825-cebcd28c-152f-4e48-a338-cba05ad9173e.png)
- ![image](https://user-images.githubusercontent.com/74208991/208288903-ea4a17d7-9ce3-4957-a140-bf0648552e84.png)
- ![image](https://user-images.githubusercontent.com/74208991/208288935-cf21823c-3b80-4055-b9c5-a6f5f2774042.png)
- ![image](https://user-images.githubusercontent.com/74208991/208289008-a68a8075-81bc-4b1e-8038-3d46add5c3be.png)
- ![image](https://user-images.githubusercontent.com/74208991/208289063-9f76df94-bb67-40db-a13a-a1f6c3bd404a.png)
- ![image](https://user-images.githubusercontent.com/74208991/208289202-a4b49886-0432-4d99-8428-8459b53c97da.png)
- ![image](https://user-images.githubusercontent.com/74208991/208289269-63e007be-e586-4a90-834a-c6ccec837b3c.png)
- ![image](https://user-images.githubusercontent.com/74208991/208289352-cefca912-84d1-4c33-a215-d8d95f181086.png)
- ![image](https://user-images.githubusercontent.com/74208991/208289386-cfb13f88-26b4-4fd2-a457-396b88de5dbe.png)
3 8 bak 
### 4.1 Introduction to the Network Layer
- ![image](https://user-images.githubusercontent.com/74208991/208291490-f5cf380c-d1dc-4cfd-a0bc-06774a95c884.png)
- ![image](https://user-images.githubusercontent.com/74208991/208291574-0e38437a-10ae-4fcf-89ef-ca89ac986584.png)
- ![image](https://user-images.githubusercontent.com/74208991/208291624-7e3112b7-eda2-49dc-8a50-b55a0f0dda27.png)
- ![image](https://user-images.githubusercontent.com/74208991/208291654-3274f5c3-f224-41e2-890a-304818da68ff.png)
- ![image](https://user-images.githubusercontent.com/74208991/208291668-718b0939-e26d-4c2c-a13d-b185a9d19dc2.png)
- ![image](https://user-images.githubusercontent.com/74208991/208291699-2596e2bd-4f20-4a98-9068-1bfd1799c119.png)
- ![image](https://user-images.githubusercontent.com/74208991/208291775-9b11b280-6adb-43b0-8ba7-1b9216a2c9c2.png)
- ![image](https://user-images.githubusercontent.com/74208991/208291851-d0a256e2-8468-4de1-8d5b-7218a839b597.png)

### 4.2 What's inside a router? Part 1.
- 1.45 bak 
- roting processor : performs control plane functions, contorls the swithch fabric and installs the forwarding tables at the input ports!!!!!
- ![image](https://user-images.githubusercontent.com/74208991/208292063-3b77180b-2a09-44a9-b4a0-829b893f3605.png)
- in link layer, the bits are assembled to link layer frames. (like ethernet frames)
- ![image](https://user-images.githubusercontent.com/74208991/208292158-87ea565e-9ce6-4fa5-bed9-4fae49ff022b.png)
- ![image](https://user-images.githubusercontent.com/74208991/208292167-6f2c764b-31c1-4890-bf65-42c3279c2e8b.png)
- generalized forwarding te mesela udp ye de bakılabılıyor. - tcp udp lerin aynı porttan gelmesine ragmen farklı output portlarına gonderılebılır mesela. burda transport network ve link layerlarına bakılabılıyor!
- ![image](https://user-images.githubusercontent.com/74208991/208292356-7580b1e1-a90e-4d9a-8b25-55e0dc25bffb.png)
- ![image](https://user-images.githubusercontent.com/74208991/208293048-cd6d8642-6b0c-427d-af3e-9372e76f5924.png)
- ![image](https://user-images.githubusercontent.com/74208991/208293212-23e0de1b-21a2-4644-8fdf-4c3a06ac7cb9.png)
- input port queuing --> if switch rate is not nr ,then packets wait for their turn in the input ports!
- ![image](https://user-images.githubusercontent.com/74208991/208293290-72286988-5675-4ae2-8227-4dde0c783a58.png)
- ![image](https://user-images.githubusercontent.com/74208991/208293331-9b82f504-85af-440e-8dd0-0b325215ad68.png)
- ![image](https://user-images.githubusercontent.com/74208991/208293366-2cdd9a94-51ac-4653-aae1-1e887704cacb.png)
- clos networks u almadın burda!   bak buna
- ![image](https://user-images.githubusercontent.com/74208991/208293435-d32d31b7-306c-4fbd-b546-5053a7d863d1.png)
- ![image](https://user-images.githubusercontent.com/74208991/208293468-0f9fc9b0-18d9-467d-acbe-44e9391c5a9c.png)
- bak
- ![image](https://user-images.githubusercontent.com/74208991/208293598-39134141-7790-4de3-b2ab-f06b72de7aeb.png)
- burda rate rn olsa da hol blocking ulusur mu bak!!
- ![image](https://user-images.githubusercontent.com/74208991/208293742-40ee8829-40dc-4a43-a1fc-0641db21ef83.png)
- ![image](https://user-images.githubusercontent.com/74208991/208293852-e9c140ea-bf2a-4d9c-b23f-48133eb2e9f7.png)
- buna bir daha bak
- ![image](https://user-images.githubusercontent.com/74208991/208294023-2ca91888-ec58-4c56-ba6b-6145f0447f16.png)
- ![image](https://user-images.githubusercontent.com/74208991/208294258-7fa57df8-2c21-47c8-b923-76b5fa74ad0e.png)
- buna bak bır daha
- ![image](https://user-images.githubusercontent.com/74208991/208294502-5ef50cbd-8f1d-4389-a170-50c190ef9d41.png)
- ![image](https://user-images.githubusercontent.com/74208991/208294544-f528112f-898f-46b4-8ef5-ae25aec119d1.png)
### 4.3 The Internet Protocol, part 1
- internets network layer deiğine ?
- ip protocol is not about routing algorithms - those are control plane functions!!!
- ıcmp protocol part of the network layer control plane
- ![image](https://user-images.githubusercontent.com/74208991/208295251-c24755dd-2853-4ceb-a9eb-481c17ec3215.png)
- ethernet linl layer frame e sıgsın dıye ığ atagram usually 1500 civarı byte olur
- header checksum since ttl is updated checksum should be recomputed!
- ![image](https://user-images.githubusercontent.com/74208991/208295519-8909d7d0-9ae4-44d0-a29e-bc23e4057bfc.png)
 - ip address link layer interface i identify eder!
 - ![image](https://user-images.githubusercontent.com/74208991/208295678-426e8561-f135-4085-a041-0d591d3a8297.png)
- su dotted notaion olayına bak!!
- ![image](https://user-images.githubusercontent.com/74208991/208295754-9302c319-a7f2-42d7-a823-a678994d420b.png)
- ![image](https://user-images.githubusercontent.com/74208991/208295811-60c7b1de-42aa-4d84-b3c7-96f606f8e45b.png)
- ![image](https://user-images.githubusercontent.com/74208991/208295874-0bd4637d-102d-4596-853e-72f3917f1218.png)
- ![image](https://user-images.githubusercontent.com/74208991/208295911-0f876c20-a7bf-4499-a465-0cca061bb3e3.png)
- ![image](https://user-images.githubusercontent.com/74208991/208295941-5e16e3bb-01a2-4b38-b68b-7d9f2f59a030.png)
- bu cıdr olayına bak
- ![image](https://user-images.githubusercontent.com/74208991/208295993-c0c8ae6c-58a1-4fd5-9f8f-2c2ece669aab.png)
- ![image](https://user-images.githubusercontent.com/74208991/208296025-a60de799-5251-4d24-a1ae-641861430821.png)
- ![image](https://user-images.githubusercontent.com/74208991/208296101-1d26fe85-320e-40e5-9dff-fa46b50b3f1e.png)
- dhcp runs over udp
- ![image](https://user-images.githubusercontent.com/74208991/208296370-7866f91e-00f4-4757-ac1e-91949ff9b0db.png)
- ![image](https://user-images.githubusercontent.com/74208991/208296437-b4b03edc-7498-4c89-ac1a-ec19494f0a73.png)
- ![image](https://user-images.githubusercontent.com/74208991/208296482-178637c2-7767-40a8-8d04-a2b0043c1f60.png)





