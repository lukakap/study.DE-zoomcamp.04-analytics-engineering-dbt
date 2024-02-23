Welcome to your new dbt project!

### Using the starter project

Try running the following commands:
- dbt run
- dbt test


### Resources:
- Learn more about dbt [in the docs](https://docs.getdbt.com/docs/introduction)
- Check out [Discourse](https://discourse.getdbt.com/) for commonly asked questions and answers
- Join the [dbt community](https://getdbt.com/community) to learn from other analytics engineers
- Find [dbt events](https://events.getdbt.com) near you
- Check out [the blog](https://blog.getdbt.com/) for the latest news on dbt's development and best practices



### My Comments

**difference between staging and core models** 

The staging layer is the first layer of transformation applied to raw data. 
It's where you perform initial cleaning and preparation of the data imported from various source systems 
before it's used in more complex transformations

The core layer (or sometimes referred to as the "transformation layer" or part of the 
"data marts" layer) is where the bulk of business logic and complex transformations are applied.
