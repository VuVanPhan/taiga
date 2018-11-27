# Taiga Integrations 
## - changing element status via commit message
```sh
   - you need commit to folder code
   git commit -m "TG-REF #STATUS-slug"
      + REF : US/Issue/Task reference of the element you want to modify
      + STATUS : new status slug to set.
         Defined status :
            - in the admin page : Admin > Attributes > Status
      - Note : you can commit multiple actions depending on the branch we could have a message like
         TG-X feature-branch#dev-in-progress dev#dev-complete master#closed
#         Ex : git commit -m "TG-1 #closed"
#              git commit -m "TG-1 #in-progress TG-3 #in-progress"
#              git commit -m "TG-1 develop #in-progress branch1 #closed"
```

