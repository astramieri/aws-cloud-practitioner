# Cost Allocation Tags

- Use **Cost Allocation Tags** to track your AWS costs on a detailed level
- Each **tag** consists of a key and a value
    - Each tag key must be **unique**
    - Each tag key can have only **one value**.
- **AWS generated tags**
    - Automatically applied to the resource you create
    - Starts with prefix **aws:** (e.g. aws:createdBy)
- **User-defined tags**
    - Defined by the user
    - Starts with prefix **user:**
- You must activate both AWS generated and user-defined tags separately before they can appear in Cost Explorer or on a cost allocation report
- Tags can be used to create **Resouce Groups**
    - Create, maintain, and view a collection of resources that share common tags
    - Manage these tags using the Tag Editor
- Free naming
    - Common tags: Name, Environment, Team, etc.



![Cost Allocation Tags](../../images/account/cost_allocation_tags.png)
