
# A simple weather app built with react .

 I am learning React. I wanted to make something practicle so,i made this weather app. Using open weather api, hooks .
  

 <h3>API<h3>
  
   
   
 It dynamically changes background according to weather conditions 
   
 
 
 <h1>Screenshot<h1>
  
![Screenshot from 2021-09-15 19-58-10](https://user-images.githubusercontent.com/64638825/133453440-c25e2ee6-f673-42b3-8cb8-810c1b78fe83.png)
  
![Screenshot from 2021-09-15 19-59-30](https://user-images.githubusercontent.com/64638825/133453415-c7c88a61-9a5f-4051-a03a-1e19b374da18.png)
  
![Screenshot from 2021-09-15 19-58-36](https://user-images.githubusercontent.com/64638825/133453431-12a669d6-c4fb-41bb-895e-5ecc777a47b6.png)
  


   
  
 
 
  

## Run Locally

Clone the project

```bash
  git clone https://github.com/gauravmandal1/weather-app
```

Go to the project directory

```bash
  cd weather-app
```

Start the server

```bash
  npm start
```

  
## API Reference

#### Get all items

```http
 https://api.openweathermap.org/data/2.5/
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `api_key` | `string` | **Required**. Your API key |

#### Get item

```
 Fetch  ${api.base}weather?q=${query}&units=metric&APPID=${api.key}
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `string` | **Required**. Id of item to fetch and query |

#### 

  
  
## Features


- Dynamic background
- Responsive UI 
- Cross platform

  
