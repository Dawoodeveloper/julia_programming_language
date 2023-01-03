# Julia_language
Before starting julia let's install julia on PC/Laptop<br>
Download julia by clicking on Download [**Download**](https://julialang.org/downloads/).
Choose according to your OS
I'm using **Ubuntu 22.04 LTS**
1st Method:
   sudo apt update
      ![1](https://user-images.githubusercontent.com/87930468/210356638-127100a3-d1c6-4d46-8e95-4e81a93399a0.png)
      <br>

  sudo apt upgrade
      ![2](https://user-images.githubusercontent.com/87930468/210356668-80c6a6fd-1641-49df-b263-0bb3ef13955a.png)

  sudo apt install snapd
      ![3](https://user-images.githubusercontent.com/87930468/210356709-93b9ef46-6749-4643-83b1-28d19ecaeeee.png)

   sudo apt install julia --classic
      ![4](https://user-images.githubusercontent.com/87930468/210356739-c894f316-37ca-4940-9df5-4fa19d9b0d0f.png)
   
   julia --version
      ![6](https://user-images.githubusercontent.com/87930468/210356863-620d36fc-d473-418d-89dd-180a497173fa.png)
   
   julia 
      ![5](https://user-images.githubusercontent.com/87930468/210356782-8cfc356f-3799-4745-bd41-a25163d61119.png)
      
  

  
  


2nd Method:
Install Julia Programming Language on Ubuntu 22.04<br>
Julia is not part of the official Ubuntu 22.04 repositories, but that doesn’t make the installation process too difficult.<br>

So, let’s get started.<br>

First, open a terminal and update the whole system completely
  sudo apt update
      ![1](https://user-images.githubusercontent.com/87930468/210356638-127100a3-d1c6-4d46-8e95-4e81a93399a0.png)
      <br>

  sudo apt upgrade
      ![2](https://user-images.githubusercontent.com/87930468/210356668-80c6a6fd-1641-49df-b263-0bb3ef13955a.png)


Then, you can download the Julia binary for Linux using this command<br>

wget https://julialang-s3.julialang.org/bin/linux/x64/1.8/julia-1.8.2-linux-x86_64.tar.gz
wget [https://julialang-s3.julialang.org/bin/linux/x64/1.8/julia-1.8.2-linux-x86_64.tar.gz](https://julialang-s3.julialang.org/bin/musl/x64/1.8/julia-1.8.4-musl-x86_64.tar.gz)

<br>
Remember that with each version of Julia, this command will be modified. So, it is recommended to visit the Julia download section to confirm the latest version.
<br>
Then, proceed to decompress it with tar.
<br>
tar zvxf julia-1.8.2-linux-x86_64.tar.gz
<br>
You will be able to use the binary, but the best thing to do is to add that directory to the system PATH.
<br>
To achieve this, edit the file ~/.bashrc.
<br>
nano ~/.bashrc
<br>
And at the end of the file add the following
<br>
export PATH="$PATH:/home/angelo/julia-1.8.2/bin"
<br>
Save the changes and close the editor
<br>
Remember that the path will depend on each user, but the general idea is to add the full path where the Julia binary is.
<br>
To apply the changes, you can run the following
<br>
source ~/.bashrc
<br>
##Testing Julia on Ubuntu
<br>
Now we just need to test Julia, for this, it is convenient to start an interactive REPL (read-evaluate-print-loop) session.
<br>
So run
<br>
julia
And you will have an output like this
 julia --version
      ![6](https://user-images.githubusercontent.com/87930468/210356863-620d36fc-d473-418d-89dd-180a497173fa.png)
   
   julia 
      ![5](https://user-images.githubusercontent.com/87930468/210356782-8cfc356f-3799-4745-bd41-a25163d61119.png)

