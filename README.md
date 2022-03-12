
# API Starter Boilerplate

Save some time seting up your next express api...




## Ready to use features:
- Express basic api ( Duh!)
- Eslint ( Airbnb Preselected Style )
- RateLimit ( [express-rate-limit](https://www.npmjs.com/package/express-rate-limit) )
- Compressed responses ( [compression](https://www.npmjs.com/package/compression) ) 
    - Use request Header ``` x-no-compression : 1``` if not need compressed responses
- Logs with [Morgan](https://www.npmjs.com/package/morgan) and Log Rotation with [rotating-file-stream](https://www.npmjs.com/package/rotating-file-stream)
## Installation

```bash
  git clone https://github.com/Kos-M/expressBoiler && cd expressBoiler
  yarn  # or npm install
  node bin/www
```
    
## API Reference (Ready For Document ```your``` Endpoints) 

#### Get all items

```http
  GET /
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `api_key` | `string` | **Required**. Your API key |

#### Get item




## Authors

- [@Kos-M](https://www.github.com/Kos-M)


## License

[MIT](https://choosealicense.com/licenses/mit/)


## Contributing

I 'll regularly update this with new ready to use tools , if needed.

Contributions are always welcome!




