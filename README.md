# JugaadHai Intership Task APIs
This Repository contains 3 dummy APIs with some sample data

- Article-list api[GET]: https://my-json-server.typicode.com/jugaadhai/assignment-app/articles/
- Article-detail api[GET]: https://my-json-server.typicode.com/jugaadhai/assignment-app/articles/:id // Replace the ":id" with actual Id, for example https://my-json-server.typicode.com/jugaadhai/assignment-app/articles/73509
- Feedback api[POST]: https://api.jhuat.in/api/Test <br>
Sample request body
```json
{
	"Name":"Jitan Gupta",
	"Feeback":"Some sample data to be passed for feedback.",
	"WillRefer":true
}
```
Sample request from postman
![image](https://user-images.githubusercontent.com/11292363/140653038-65c29212-85f0-4492-86b6-e72f854d60fa.png)


### Images
If you will see image url in above api it looks something like `images/2021819152533scaler-academy-squarelogo.png` which won't be a valid path for your application, so prepend `https://jugaadhai.github.io/assignment-app/` before your images to access the images. <br>
Example: https://jugaadhai.github.io/assignment-app/images/2021819152533scaler-academy-squarelogo.png
