# Centralized property store

Store all your hardcoded values in a centralized transform per environment and reference them wherever needed in your other transforms. This not only helps in maintaining a single source of truth for your hardcoded values but also makes it easier to update or modify them in the future.

# List of transforms to achieve

## Get Environment

This is used to tell in which  environment you are in. This ia a static transform and return a "development","sandbox", or "production". 
