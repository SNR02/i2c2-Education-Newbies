# i2c2-Education-Newbies
<h2>This is a step-by-step guide on how to access and use the i2c2-Education-Newbies project. </h2>
<h3>Method-1 :-</h3>
Create a new folder and open git bash in that particular directory
<br><br>

![image](https://user-images.githubusercontent.com/109890201/231835500-c819ed96-f940-41e3-92d5-d9d533b13696.png)
<br><br>
Once the git bash is opened, copy the repository link and clone the repository using the following git command
<br><br>
### `git clone "https://github.com/SNR02/i2c2-Education-Newbies.git"`
<br><br>

![image](https://user-images.githubusercontent.com/109890201/231835596-5f7b4257-cde3-4cc7-86c0-ae65dcdb1041.png)
<br><br>
Once the repository is cloned, you'll find a "Frontend" and a "Backend" folder
Now open "Frontend" folder and open a new terminal in that folder and install dependencies using
### `npm install`
<br><br>

![image](https://user-images.githubusercontent.com/109890201/231845562-9f0a73e1-2807-42e1-922e-2738e7ef31da.png)
<br><br>
Do the same processs for the Backend folder 
<br><br>

![image](https://user-images.githubusercontent.com/109890201/231845917-608f172b-f4c6-44c7-8f58-4ea0993ad90e.png)

Now run both the "Frontend" and "Backend" one after one by entering the following command in the terminal (Notice that we have to enter the command in the termianl we opened in the Frontend folder as well in the terminal we opened in the Backend folder)
<br><br>
### `npm start`

![image](https://user-images.githubusercontent.com/109890201/231846718-f0bcdca4-3f5e-4ded-a230-9df25ca04608.png)

Now the application opens in "localhost:3000"

![image](https://user-images.githubusercontent.com/109890201/231846860-b74f60ff-54f1-4b3b-ab99-084e5399d950.png)

If any issues are encountered and the application is taking forever to open, kindly go through the following steps:
Enter these commands in the terminal which we opened in "Frontend" folder
### `npm audit fix --force`
### `npm fund`

<br><br>
<h3>Method-2 :-</h3>
<h4>Readily deployed and accessible Backend Link</h4>
<a href="https://edumindz-backend.vercel.app/">Backend Link</a>
<br><br>

![image](https://user-images.githubusercontent.com/109890201/231837273-ca707346-a0b0-4728-9252-0e59800d2174.png)

<h5>The above link will redirects to "localhost:3000" if clicked</h5>
<br><br>
Once after opening the backend link, kindly clone the Frontend Folder, for this the steps are :-
<br><br>
Create a new folder and open git bash in that particular directory
<br><br>

![image](https://user-images.githubusercontent.com/109890201/231835500-c819ed96-f940-41e3-92d5-d9d533b13696.png)
<br><br>
Once the git bash is opened, copy the repository link and clone the repository using the following git command
<br><br>
### `git clone "https://github.com/SNR02/Edumindz-Frontend.git"`

![image](https://user-images.githubusercontent.com/109890201/231844765-6da731af-f601-4708-a6c7-eb076e3e573d.png)
<br><br>
Once the repository is cloned, open a new terminal in that folder
<br><br>

![image](https://user-images.githubusercontent.com/109890201/231836227-52a406c2-1c0c-4aa4-8a20-80e5e727d89b.png)

Firstly, Install the dependencies using the following command
<br><br>
### `npm install`
Once the dependencies are installed, run the react app using the following command
### `npm start`

![image](https://user-images.githubusercontent.com/109890201/231836826-68bbd306-3f34-4870-aadb-d457db3923e9.png)

<h5>This will open the application in "localhost:3000"</h5>

