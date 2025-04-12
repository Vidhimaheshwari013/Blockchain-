  # IPFS
   Commands (IPFS)
1.	Install the IPFS through WSL: wget https://dist.ipfs.tech/kubo/v0.32.1/kubo_v0.32.1_linux-amd64.tar.gz Or 
    we get https://github.com/ipfs/kubo/releases/download/v0.32.1/kubo_v0.32.1_linux-amd64.tar.gz
2.	tar -xvzf kubo_v0.32.1_linux-amd64.tar.gz
3.	Kubo is a reference implementation of IPFS in Go: cd kubo 
4.	ls
5.	sudo bash install.sh
6.	ipfs –version
7.	ipfs init
8.	ipfs daemon
9.	On Browser: http://127.0.0.1:5001/webui
10.	To run ipfs daemon in background: ipfs daemon > ipfs.log 2>&1 &
11.	This is daemon ID: [1] 772
12.	Add file: echo "Hello, IPFS!" > hello.txt
13.	ipfs add hello.txt
14.	ipfs cat <CID>
15.	Add a directory: mkdir myfolderecho "File 1 content" > myfolder/file1.txt echo "File 2 content" > myfolder/file2.txt
16.	ipfs add -r myfolder
17.	ps aux | grep ipfs
18.	kill <PID>
19.	in Browser you can directly run this to see the IPFS: https://ipfs.io/ipfs/QmWd9cavD8UGZQcqYBVhZqs2Jure5W9cgxR7S6TC4StfZe

![image](https://github.com/user-attachments/assets/4217e874-aa2c-4cda-9983-cf8432160d5f)

![image](https://github.com/user-attachments/assets/6870ad98-bfa7-47b8-8d2a-c0acfd10fbba)

![image](https://github.com/user-attachments/assets/4cdab6f1-71ca-450e-9428-09b0e321f414)

![image](https://github.com/user-attachments/assets/101d2722-0f4a-4c90-99eb-8fc8cfcc6aa4)

![image](https://github.com/user-attachments/assets/cdc76fac-cabd-4c61-b1cf-85ef0c659bf4)

![image](https://github.com/user-attachments/assets/1351ecc6-7780-4a6a-8340-e7ba68be63b6)

![image](https://github.com/user-attachments/assets/796f39be-a326-48c0-86e3-5660c688ee2d)

![image](https://github.com/user-attachments/assets/1b503390-116b-4159-81dc-ecc0359ed65d)

![image](https://github.com/user-attachments/assets/8519edd2-22d7-4b9a-9b48-b6efc63228cc)







