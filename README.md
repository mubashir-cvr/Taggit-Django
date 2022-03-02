## Taggit-Django



### Install Package
```
pip install django-taggit

```

### Settings
```

INSTALLED_APPS = [
    ....
    ....
    'taggit'
]
```

### Models Import

```
from taggit.managers import TaggableManager

```

### Models model
```
class Post(models.Model):
  title = models.CharField(max_length=255)
  tags = TaggableManager()

```
