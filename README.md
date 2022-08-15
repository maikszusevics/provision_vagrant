# provision vagrant

![image](https://user-images.githubusercontent.com/110176257/184674576-0d17fcb8-b098-4058-a484-0d42962e7e0a.png)

I have automated the app dependencies and startup using 
```ruby
config.vm.provision "shell", inline <<-SHELL 
```
![image](https://user-images.githubusercontent.com/110176257/184671351-c0b99c4d-838a-4e59-9383-e6a5404408d6.png)

Now after running `vagrant up`, it initialises the VM and ends by showing the app is running:

![image](https://user-images.githubusercontent.com/110176257/184674212-8a3e0dbd-2409-4f9b-a3d2-01a6e0c7d379.png)
