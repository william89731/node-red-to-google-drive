# google sheets-node red

![immagine](https://user-images.githubusercontent.com/68069659/106394915-96a2e400-63ff-11eb-9a4c-f2beeb6d3eff.png)

Save your data in google drive and create graphs to have everything under control

# Step-1: google spreadsheet

![immagine](https://user-images.githubusercontent.com/68069659/106394419-c7354e80-63fc-11eb-8f7c-2c15818dfad4.png)

Go to **google drive** and create a new module:

![immagine](https://user-images.githubusercontent.com/68069659/106382302-ea410d80-63be-11eb-972d-2c2c17c7064f.png)

write a title to the form question:

![immagine](https://user-images.githubusercontent.com/68069659/106389578-4ff3c080-63e4-11eb-9179-650fbb6fdd73.png)

generate links:

![immagine](https://user-images.githubusercontent.com/68069659/106383391-ecf33100-63c5-11eb-96f9-42992e1adb18.png)

write any number to get the link:


![immagine](https://user-images.githubusercontent.com/68069659/106389920-38b5d280-63e6-11eb-9c99-1e3bafd409e3.png)

copy and paste the link into your favorite text editor:

![immagine](https://user-images.githubusercontent.com/68069659/106390138-37d17080-63e7-11eb-82c2-e071b418faa1.png)

replace **viewform?usp=pp_url&entry.587731667=34**  with  **formResponse?entry.987113020={{payload}}** :

![immagine](https://user-images.githubusercontent.com/68069659/106390176-6b13ff80-63e7-11eb-8cce-d268c85dcc0f.png)

we will need the new link obtained for node red's http request:

![immagine](https://user-images.githubusercontent.com/68069659/106384047-617b9f00-63c9-11eb-9ee7-009fe896ed80.png)

create a new worksheet or add an existing one:

![immagine](https://user-images.githubusercontent.com/68069659/106384199-eebef380-63c9-11eb-8fd7-eb4996224b6d.png)

now we have our chart ready to use:

![immagine](https://user-images.githubusercontent.com/68069659/106384288-54ab7b00-63ca-11eb-8c2b-18292536e6b7.png)



# step-2: node red


![immagine](https://user-images.githubusercontent.com/68069659/106384407-fc28ad80-63ca-11eb-87f5-9fcad3e43e04.png)

get  **http request** node, and paste link before create

![Screenshot_20210411_180200](https://user-images.githubusercontent.com/68069659/114311733-3495e780-9af0-11eb-8831-e8de83e538c2.png)

 save the data in the global



![immagine](https://user-images.githubusercontent.com/68069659/106384484-5e81ae00-63cb-11eb-8d15-126c321f3602.png)

deploy the flow [here]()


# step3: graphic




