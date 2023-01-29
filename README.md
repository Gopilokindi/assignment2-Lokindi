# assignment2-Lokindi
# Lokindi Gopi
###### Cricket

My favourite team sport is **Cricket** Because It was have all types of mixed **Feelings** to enjoy every person in the Stadium.<br>It was so **Exciting** game when it comes to T20 format games.<br>Mainly I like to watch this type of **Qualities** like sportiveness,Team Spirit,Aggression,calmness while playing in the Cricket Sport.
 
---
### Just Do Cricket
my  favorite team is **Royal Challengers Bangalore.**<br>
1. Virat kohli
2. Glenn Maxwell
3. Jason Behrendorff
* Mi Cape Town
* Gujarat Titans
* Lucknow Super Giants

**[AboutMe](AboutMe.md)**

---
### wanderlust
This is Traveling Table Information.
| Country | Reason | No of days |
| --- | --- | ---: |
| Goa | Best Place to Hangout | 10 |
| France | Best place to Have nice views | 15 |
| UAE | Best Place to visit waterless mountains | 18 |

---
### Funny Quotes
>The best way to teach your kids about taxes is by eating 30 percent of their ice cream. *Bill Murray*

>Knowledge is like underwear. It is useful to have it, but not necessary to show it off. *Bill Murray*

---
### Code Fencing
>Get The First Image From a Post.click here to go stackoverflow <https://stackoverflow.com/questions/21975301/how-to-get-the-first-image-from-post>

```
function catch_that_image() {
  global $post, $posts;
  $first_img = '';
  ob_start();
  ob_end_clean();
  $output = preg_match_all('/<img.+?src=[\'"]([^\'"]+)[\'"].*?>/i', $post->post_content, $matches);
  $first_img = $matches[1][0];

  if(empty($first_img)) {
    $first_img = "/path/to/default.png";
  }
  return $first_img;
}
```
click here to go css-tricks <https://css-tricks.com/snippets/wordpress/get-the-first-image-from-a-post/>


