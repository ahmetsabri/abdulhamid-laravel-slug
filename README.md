# Fatih Laravel Search
A laravel package to search via your models .

installation : 

`composer require ahmetsabri/fatih-laravel-search`

Usage :

- use `Sluggable` trait in your model
- Define `$sluggable` property in your model to select which columns to be slug

Example :

```  
use Ahmetsabri\FatihLaravelSearch\Searchable;

class Post extends Model {

  use Sluggable ;
  protected $sluggable = 'title';
  

```
### That's it !
