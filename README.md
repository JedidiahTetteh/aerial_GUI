To connect to drone through USB in Linux:
	1) mavproxy.py --master=/dev/ttyUSB0 --out=127.0.0.1:14555
	2) python hydra_server.py
	3) to test:
		telnet localhost 5000
	4) Launch Qt Application
	
	
	
	
To connect to drone through UDP in linux

	1) mavproxy.py --master=udp:127.0.0.1:14550 --out=127.0.0.1:14555
	2) python hydra_server.py
	3) to test:
		telnet localhost 5000
	4) Launch Qt Application
