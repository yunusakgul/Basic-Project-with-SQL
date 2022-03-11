# Basic-Project-with-SQL
Basic Project to use Sql functions along the way

The main idea behind this project is to use what I've been learning about SQL, it will not be about EDA, at least not until I've learned enough.

I believe best way to learn a software is to use it. I have been attending online courses from websites(such as Datacamp,Coursera). I am going to wonder something about the 
open-base datasets then I am going to try finding the solution. It'd be better if I use Python for visualization along the way, but I am not there yet.

I am going to use the movies dataset, I found on Kaggle, also can be found it repository.

Here is a summary of data types and columns:

![image](https://user-images.githubusercontent.com/66702893/156434648-e1bebb10-3b61-4792-b628-2242d324b56a.png)



First I would like to order most liked movies: 

Datasets I downloaded was splitted in two, covering different years. I needed to combine this in order to get one. 


![image](https://user-images.githubusercontent.com/66702893/156446749-30c86139-b798-486d-b6a4-a8c3e687ac64.png)

With Ranking column:

![image](https://user-images.githubusercontent.com/66702893/156563853-ffad0cb9-82cf-4f89-a1cf-7e1fac3c9848.png)


It would be nice to compare most winning genres, to see there is a popular or more profitable than the others. 


![image](https://user-images.githubusercontent.com/66702893/157967528-e3320d0a-f5a3-40cf-90bc-11d1e2b0789a.png)

It appears that Action and Adventure are involved in most winning combinations.


I would like to investigate the relationship between imdb points and gross. Did movies with higher imdb points earn more than the others? I am going to divide this question in two, because it wouldn't be fair to compare old movies with this perspective considering viewers did not have access to imdb. So I am going to calculate the second one with the movies released after 2000. 


When this data is divided into 20 according to the descending order of imdb points and not including movies without a gross information, this conclusion appears. It doesn't seem like there is a connection with imdb points and total earnings. Once again I should emphasize most loved movies were released before imdb was ever founded, so this can be misleading. 

It is also suprising that movies with second highest imdb points are all the way back in this list.


![image](https://user-images.githubusercontent.com/66702893/157973958-92843620-a9b0-4549-b637-3287dff325ca.png)


Let's see this for the after 2000 releasing:

![image](https://user-images.githubusercontent.com/66702893/157974926-ea853c06-19bb-43c7-a9eb-8cf1de313e74.png)

Including movies released after 2000 seems more reasonable, but table is still diversed comparing to the imdb points. It is hard to say movies with greater points earned more than the lower ones. Other things related to the cinema should be considered such as marketing, actors who were involved. A movie might be well profitable just because famous actors were in it. 





