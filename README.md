#  Project Reddit-data

# Problem statement

I examined the data for the reddit which is social media website where users can discuss about a particular topic in subreddits. They can post content and get downvotes and upvotes for the post. My job was to find the most trending things in terms of growth where people have shown maximum interest.

-----------
# Implementation

1. Took the feel of the table. Three Tables-users, posts, subreddits
2. Identify Primary keys and Foreign keys
3. Total count of different subreddits
4. What user has the highest score?
   What post has the highest score?
   What are the top 5 subreddits with the highest subscriber_count?
5. Used a LEFT JOIN with the users and posts tables to find out how many posts each user has made
6. To see existing posts where the users are still active, so use an INNER JOIN to write a query to get these posts
7. Some new posts have been added to Reddit!
   Stack the new posts2 table under the existing posts table to see them
8. To find out which subreddits have the most popular posts. We’ll say that a post is popular if it has a score of at least 5000
9. To find out the highest scoring post for each subreddit
10.Calculate the average score of all the posts for each subreddit

----------
# Output

# Output1 :

<img width="872" alt="Database schema reddit" src="https://user-images.githubusercontent.com/95974943/147754570-ab215139-b153-4eee-b4e9-04d1dd02cf43.png">


 
<img width="872" alt="Tables" src="https://user-images.githubusercontent.com/95974943/147754508-2b1410e7-9309-48a2-8ce0-e46ffca88898.png">
 
 


# Output2(final crux):
I was able to see find out which content is most popular and what type of posts are trending. How many users are active and how many are not, so that after finding their details they can be notified for more participation. With these objectives we can improve user participation.


<img width="464" alt="Average Score of Subreddits" src="https://user-images.githubusercontent.com/95974943/147754588-80eacf3a-2349-4ec7-b812-88e19b6d11d4.png">









