## axum_boilerplate

This repository is a functioning server boilerplate built with [Axum](https://github.com/tokio-rs/axum).  
 It serves on port 8000 and has a health check route at "/".

**To start the server :**

```
cargo run
```

**Dependencies:**

- axum = 0.6.2
- serde = 1.0.152
- tokio = 1.24.1
- tower-http = 0.3.5
- tracing = 0.1.37
- tracing-subscriber = 0.3.16
