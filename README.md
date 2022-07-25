# Candidate Test

This repo contains a simple Django project with a blog called `video` containing the model `Post`.

## Task:

This task aims to evaluate your understanding of the Django ORM and your ability to write clear pull requests. To complete this task, create a throwaway github account, fork the repo and carryout the following steps:

1. Fix `video.views.py` so that the two views efficiently fetch the `Post` objects.
2. Add logic to increment `Post.page_views` each time someone views a certain post.
3. Add a test for this new functionality in `video/tests`.
4. Write a pull request with your new code.

Tests can be run with:

```
coverage run -m pytest
```

The code that you write in this task is used only to evaluate your candidature, it will not be used in production.