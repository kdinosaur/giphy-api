# giphy-api
Learning to query the Giphy API

	//Create gif on page
	var gif = document.createElement('img');
	gif.setAttribute('src', gifUrl);
	document.body.appendChild(gif)
 
![giphy-api-working-basic](https://github.com/kdinosaur/giphy-api/assets/9345819/e7ead402-6bf2-49c6-ba0d-9ddfe9ed0cee)

Added a title

	//Add gif title
	var titleText = jsonData.data.title;
	var title = document.createElement('h3');
	title.innerText = titleText;
	document.body.appendChild(title);
})

![with-title-added](https://github.com/kdinosaur/giphy-api/assets/9345819/783053e2-3cc7-459e-a88e-17ebcddc3229)





