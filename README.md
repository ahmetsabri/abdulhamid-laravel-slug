# Abdulhamid Laravel Search
A laravel package to slugg columns via your models .

installation : 

`composer require ahmetsabri/abdulhamid-laravel-slug`

Usage :

- use `Sluggable` trait in your model
- Define `$sluggable` property in your model to select which columns to be slug

Example :

```  
use Ahmetsabri\Abdulhamid\Searchable;

class Post extends Model {

  use Sluggable ;
  protected $sluggable = 'title';
  

```
### That's it !
