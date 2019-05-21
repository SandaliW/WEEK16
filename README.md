# WEEK16
#  Data transfer performance measure using "time" command
Organise the experiment on two different scales:

    copy files with specified size to another folder in the same system 
    copy files with specified size to another system over the network using "nc" tool and two distinguished protocols:
        UDP
        TCP

Simultaneously, capture network traffic utilising  TCPDUMP library (bash, Python,  C++, or Java)

# dd if=/devz/zero of=fil.dat bs=1024 count=1  #this for 1MBbits/s
# to connect the two terminals
#make both terminal directory to
#mkdir WEEK6
#cd mkdir
#pwd  #make sure we are in WEEK6 file
## dd if=/devz/zero of=fil.dat bs=1024 count=1  #this for 1Mbits/s
# changing count and bs get files for 1, 10 and 100 Mbits/s
#connect two terminals
# cat fil1.dat | nc -l 1234 
#nc -l 1234 > fil1out.dat

