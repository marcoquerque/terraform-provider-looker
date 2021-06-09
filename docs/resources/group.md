---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "looker_group Resource - terraform-provider-looker"
subcategory: ""
description: |-
  
---

# looker_group (Resource)



## Example Usage

```terraform
resource "looker_role_groups" "embed_role_groups" {
  role_id   = looker_role.embed_role.id
  group_ids = ["${looker_group.embed_group.id}"]
}
```

<!-- schema generated by tfplugindocs -->
## Schema

### Required

- **name** (String)

### Optional

- **id** (String) The ID of this resource.

