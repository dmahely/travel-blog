## Deploy Static Website on AWS

This is a basic static website provided by Udacity in the [Cloud Developer Nanodegree](https://www.udacity.com/course/cloud-developer-nanodegree--nd9990). The purpose is to deploy it to AWS using S3 and CloudFront.

The files included are: 

* `index.html` - The Index document for the website.
* `/img` - The background image file for the website.
* `/vendor` - Bootssrap CSS framework, Font, and JavaScript libraries needed for the website to function.
* `/css` - CSS files for the website.

## Deployment steps

1. Create an S3 bucket

![](https://user-images.githubusercontent.com/21047475/101395750-d065db80-38e3-11eb-90aa-aefc73f38fac.png)

2. Update bucket policy

![](https://user-images.githubusercontent.com/21047475/101396232-744f8700-38e4-11eb-9628-ef9e258b8bdd.png)

3. Upload website files to bucket

![](https://user-images.githubusercontent.com/21047475/101396283-86312a00-38e4-11eb-84c7-5950272b0a15.png)

4. Enable static website hosting option on the bucket

![](https://user-images.githubusercontent.com/21047475/101396409-ba0c4f80-38e4-11eb-9ed6-0f2f657cd4df.png)

5. Create CloudFront distribution on the bucket

![](https://user-images.githubusercontent.com/21047475/101396506-da3c0e80-38e4-11eb-9753-b7538784957d.png)

6. Visit CloudFront URL

![](https://user-images.githubusercontent.com/21047475/101397829-a4982500-38e6-11eb-85aa-9dd5df1fd164.png)

7. Be redirected to the website

![](https://user-images.githubusercontent.com/21047475/101397916-c5f91100-38e6-11eb-8726-e0a1405af7ab.png)
