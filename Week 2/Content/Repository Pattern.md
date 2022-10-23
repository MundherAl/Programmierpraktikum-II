- Best practice to access data from a database is a so-called repository pattern.
- Typically looks like the following:
```Java
public class PostRepository {
	public Post findPostByID(PostID id) {
		// loads post from database
	}
	public void save(Post post) {
		// saves changes in database
	}
}
```

- A use case may look like this:
```Java
public void like(PostID id) {
	Post post = postRepository.findPostByID(id);
	post.like();
	post.save(post);
}
```
