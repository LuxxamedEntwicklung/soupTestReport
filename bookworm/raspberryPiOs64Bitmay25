Tests on Raspbian 64Bit from May 2025, install Java25 JDK, Python 3, switch on SPI Com and setup Wifi with some SSD, readout the ip adress of the system

1.Install on Raspberry PI5 with PI PCI M2 SSD and run OS

- [X] testrun ok
- [ ] testrun failed

2. run Python3 on PI5 and start GPIOrunner with socket_to_serial Branch PI5

- [X] testrun ok
- [ ] testrun failed

3. install channel Boards on BUS Test Board and run therapytest with Testserver, control SPI Signal MOSI, MISO, SCLK and test Signal on SlaveSelectors

- [X] testrun ok
- [ ] testrun failed

4. Run JavaBridge Software HD2000 Service Server with Simulator Therapy

- [X] testrun ok
- [ ] testrun failed

5. Run HelloJPro JPro Test for ability of running

- [X] testrun ok
- [ ] testrun failed

6. Run JPro Test and Testserver for Therapytest for 24hours, after readout protocoll for errormessages

- [X] testrun ok
- [ ] testrun failed

7. Restart Testsetting 25 times with interrupting power source and reconnecting it, let therapy startup automatically and take care that therapy starts up every time

- [X] testrun ok
- [ ] testrun failed

8. Switch SSH port off and start the system, try to connect via ssh.

- [X] testrun ok, ssh not available anymore
- [ ] testrun failed

9. Stop SSH programmatically and restart it through socket.

- [X] testrun ok, ssh was not available anymore, after restarting over websocket it was available.
- [ ] testrun failed

10. Run the remote benchmarks and try availability of socket service and hd2000 server over socket connection from external 
https://github.com/TheRemote/PiBenchmarks are used to processor load of 50%

- [X] testrun ok, Socket connection worked as awaited
- [ ] testrun failed

11. Test user password protection for connections over network

- [X] testrun ok, users have to invoke their password before can enter the server
- [ ] testrun failed

12. Try DNS attsck for password entering with known username

- [X] testrun ok, pi paused the login after three wrong logins for 15 seconds every time. When always autoconnecting with a new session this behavior stopped, after 24 hours of continous load there was also no connection possible.
- [ ] testrun failed

13. Summary

- [X] Test passed
- [ ] Test failed

tested by: Thorsten Stüker 14.-21.09.2021
