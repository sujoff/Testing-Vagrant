Here,\
I'll document my a basic process of spinning up three Ubuntu vm in your machine.

Step 1: Installed Vagrant (use official documentation, chatgpt/gemini if you have no idea)

step 2: Installed Oracle VM virtualbox

step 3: Install git bash (I prefer it for some reason. You can use powershell/terminal as well), run `mkdir ubuntu`, `cd ubuntu` and type `vagrant init` and enter

step 4: I'm goint to spin up three vm named `first`, `second` and `third`

vagrant uses boxes (think of them as base os image) to up the VM. you can find your favourite boxes at (https://app.vagrantup.com/)


Being a Gen-z engineer, I generated a vagrantfile with above description using Google Gemini and edited it to Vagrantfile ( yes it don't have any extension).

Step 4: Now run `vagrant up`

Now it should start creating your three ubuntu vm machines like:
![image](https://github.com/sujoff/Testing-Vagrant/assets/91075040/a39cf95c-0ad9-4de9-a901-18dcb4a54095)

Now you can ssh to your vm using `vagrant ssh {name of your vm})` like below. I'll use `vagrant ssh first` for now.

![image](https://github.com/sujoff/Testing-Vagrant/assets/91075040/8faeead9-3a70-4e0d-a968-d1cddbe4ee45)

Done. Now you've successfully ssh'ed to your newly created Ubuntu virtual machine.




