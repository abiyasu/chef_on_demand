# 📚 Project Name

Chef on Demand, a web app enabling users to hire and rent personal chefs for tailored cuisine experiences.

![image](https://github.com/abiyasu/chef_on_demand/assets/128378933/3791d97f-c059-4dcf-a393-ca861b3263e4)


<br>
App home: https://chef-on-demand-e3a87d9137d5.herokuapp.com/
   

## Customer reservation page
![image](https://github.com/abiyasu/chef_on_demand/assets/128378933/264dc160-4878-4ffd-8514-e84df1a6938f)
## Customer reservation history
![image](https://github.com/abiyasu/chef_on_demand/assets/128378933/f20640f1-958e-4814-9bd3-06080b2de9d0)
## Customer reservation Detail
![image](https://github.com/abiyasu/chef_on_demand/assets/128378933/0ab13213-7d6e-46e9-9d98-a30e2c1d51cb)


### Setup

Install gems
```
bundle install
```

### ENV Variables
Create `.env` file
```
touch .env
```
Inside `.env`, set these variables. For any APIs, see group Slack channel.
```
CLOUDINARY_URL=your_own_cloudinary_url_key
```

### DB Setup
```
rails db:create
rails db:migrate
rails db:seed
```

### Run a server
```
rails s
```

## Built With
- [Rails 7](https://guides.rubyonrails.org/) - Backend / Front-end
- [Stimulus JS](https://stimulus.hotwired.dev/) - Front-end JS
- [Heroku](https://heroku.com/) - Deployment
- [PostgreSQL](https://www.postgresql.org/) - Database
- [Bootstrap](https://getbootstrap.com/) — Styling
- [Figma](https://www.figma.com) — Prototyping

## Team Members
- [Aaron Randall](https://github.com/aaronasherrandall)
- [Buruburu Luo](https://github.com/Buruburu1101)
- [Valerie Keeton](https://github.com/vkeeton)
- [Abiyasu Zhang](https://www.linkedin.com/in/dougberkley/)

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
This project is licensed under the MIT License
