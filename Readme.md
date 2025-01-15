> [!NOTE]  
> This Project is a work in progress and is not suitable to be used at this moment.

# Relia

Reliable high volume forms service to collect and manage data. Blazingly fast and highly scalable with builtin load balancer and server management tools. 


## To build and run

To build this project run

```bash
  cargo build --release
```

To run locally

```bash
  # Start redis and postgres from docker compose script.
  docker compose up 

  # Run the server
  cargo run --release  
