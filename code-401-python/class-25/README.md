# READ 25

# DJANGO (DRF Permessions)

### What are permissions in DRF?

> In DRF, permissions, along with authentication and throttling, are used to grant or deny access for different classes of users to different parts of an API. Authentication and authorization work hand in hand. Authentication is always executed before authorization.

### How do I add permissions in Django?
>By default, Django provides a built-in authorization (permissions).
...
Working with Django's Built-in Permissions

>1:add: user.has_perm('product.add_order')

>2:change: user.has_perm('product.change_order')

>3:delete: user.has_perm('product.delete_order')

>4:view: user. has_perm('product.

### What is the difference between Django and DRF?
> With DRF, one can write REST APIs with just a few lines of code. The Django REST will return only a JSON response which can be accessed by anybody who wishes to use it. All they have to do is write code that will consume the API (that is, de-serialize the JSON response).

### Can I use DRF without Django?

>One cannot use DRF without Django since DRF is not an autonomous framework.