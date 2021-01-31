# Step-1: google-fogli

go to google drive and create a new module:

![immagine](https://user-images.githubusercontent.com/68069659/106382302-ea410d80-63be-11eb-972d-2c2c17c7064f.png)

write a title to the form question:

![immagine](https://user-images.githubusercontent.com/68069659/106389578-4ff3c080-63e4-11eb-9179-650fbb6fdd73.png)

generate links:

![immagine](https://user-images.githubusercontent.com/68069659/106383391-ecf33100-63c5-11eb-96f9-42992e1adb18.png)

copy and paste the link into your favorite text editor:

![immagine](https://user-images.githubusercontent.com/68069659/106383497-bbc73080-63c6-11eb-8439-b2aad7a83710.png)

replace **viewform?usp=pp_url&entry.987113020=Opzione+1**   with **formResponse?entry.987113020={{payload}}** :

![immagine](https://user-images.githubusercontent.com/68069659/106383645-79522380-63c7-11eb-87cf-d116df86929b.png)

we will need the new link obtained for node red's http request:

![immagine](https://user-images.githubusercontent.com/68069659/106384047-617b9f00-63c9-11eb-9ee7-009fe896ed80.png)

create a new worksheet or add an existing one:

![immagine](https://user-images.githubusercontent.com/68069659/106384199-eebef380-63c9-11eb-8fd7-eb4996224b6d.png)

now we have our chart ready to use:

![immagine](https://user-images.githubusercontent.com/68069659/106384288-54ab7b00-63ca-11eb-8c2b-18292536e6b7.png)

# step2: node red

get  **http request** node, and paste link before create:

![immagine](https://user-images.githubusercontent.com/68069659/106384407-fc28ad80-63ca-11eb-87f5-9fcad3e43e04.png)

this is the flow for http request:

![immagine](https://user-images.githubusercontent.com/68069659/106384484-5e81ae00-63cb-11eb-8d15-126c321f3602.png)

deploy the flow [here]()

# step3: graphic




