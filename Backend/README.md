# Happy Backend

![Typescript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![Node](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/Express.js-404D59?style=for-the-badge)
![SQLite](https://img.shields.io/badge/SQLite-07405E?style=for-the-badge&logo=sqlite&logoColor=white)
![TypeORM](https://img.shields.io/badge/TypeORM-07405E?style=for-the-badge&logo=typeorm&logoColor=white)

## 🚀 Installing Happy Backend

To install **Happy Backend**, follow the next steps:

In your terminal:

```
# Clone this repository
git clone git@github.com:RafaelPrado409/Happy.git
```
```
# Acess Happy folder
cd Happy
```
```
# Acess Backend folder
cd Backend
```
```
# Install de dependencies
npm install
```

### Call the routes

```
Name: Create Orphanage
URL: http://localhost:xxxx/orphanages
Method: POST
Body: Multipart Form:
                      name:
                      latitude(can use google maps):
                      longitude(can use google maps):
                      about:
                      instructions:
                      opening_hours:
                      open_on_weekends:
                      images:
```

```
Name: List Orphanages
URL: http://localhost:xxxx/orphanages
Method: Get
Body: No Body
```

```
Name: Orphanage Details
URL: http://localhost:xxxx/orphanages/:id
Method: Get
Body: No Body
```
