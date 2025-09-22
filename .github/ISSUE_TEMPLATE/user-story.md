---
name: User Story
about: user stories based on Stakeholder requirements
title: ''
labels: ''
assignees: ''

---

### **1. Create a Product**

## User Story

**As a** catalog manager  
**I need** the ability to create a product in the catalog  
**So that** I can add new items for sale

## Acceptance Criteria

- [ ] Given I am logged in as a catalog manager  
  When I submit a new product with valid details  
  Then the product should be added to the catalog

### **2. Retrieve a Product**

## User Story

**As a** customer  
**I need** the ability to retrieve a product from the catalog  
**So that** I can view its details before purchasing

## Acceptance Criteria

- [ ] Given a product ID  
  When I request product details  
  Then the system should return the product information


### **3. Update a Product**

## User Story

**As a** catalog manager  
**I need** the ability to update a product in the catalog  
**So that** I can keep product information accurate

## Acceptance Criteria

- [ ] Given I am logged in and have access to a product  
  When I update its details  
  Then the catalog should reflect the updated information


### **4. Delete a Product**

## User Story

**As a** catalog manager  
**I need** the ability to delete a product from the catalog  
**So that** I can remove outdated or discontinued items

## Acceptance Criteria

- [ ] Given a product ID  
  When I choose to delete the product  
  Then it should be removed from the catalog


### **5. Like a Product**


## User Story

**As a** customer  
**I need** the ability to like a product in the catalog  
**So that** I can express interest in it

## Acceptance Criteria

- [ ] Given I am viewing a product  
  When I click the like button  
  Then the product's like count should increase


### **6. Dislike a Product**

## User Story

**As a** customer  
**I need** the ability to dislike a product in the catalog  
**So that** I can provide feedback or indicate disinterest

## Acceptance Criteria

- [ ] Given I am viewing a product  
  When I click the dislike button  
  Then the product's dislike count should increase


### **7. List All Products**

## User Story

**As a** customer  
**I need** the ability to list all products in the catalog  
**So that** I can browse available items

## Acceptance Criteria

- [ ] Given I access the catalog  
  When I request all products  
  Then the system should return a list of all available products


### **8. Query Subset of Products**

## User Story

**As a** customer  
**I need** the ability to query a subset of products in the catalog  
**So that** I can find items that match my preferences

## Acceptance Criteria

- [ ] Given I apply filters (e.g., category, price range)  
  When I submit the query  
  Then the system should return matching products


### **9. Host in the Cloud**

## User Story

**As a** devops engineer  
**I need** the catalog to be hosted in the cloud  
**So that** it is scalable and accessible from anywhere

## Acceptance Criteria

- [ ] Given the application is deployed  
  When accessed via the internet  
  Then it should be available through a cloud-hosted URL


### **10. Automate Deployments**

## User Story

**As a** devops engineer  
**I need** automated deployments for the catalog  
**So that** updates are reliably and quickly pushed to production

## Acceptance Criteria

- [ ] Given a new commit is pushed to the main branch  
  When CI/CD pipeline runs  
  Then the updated application should be deployed to the cloud
