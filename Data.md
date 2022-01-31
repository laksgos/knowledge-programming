# Data

### todo item

#### invariant
  - id must be unique within (item, project, group)

// intrinsic data
```json
item: {
  "complete": false,
  "description": "",
  "dueDate": "2012-04-23T18:25:43.511Z",
}
```

// view data
```json
item: {
  "id": 123,
  "displayOrder": 3,
}
```

// method
crud()
setPriority()

### todo project

#### invariant
  - id must be unique within (item, project, group)
  - description must be unique within (project, group)

```json
project: {
  "id": 123,
  "description": "",
  "displayOrder": 3,
  "items": [],
}
```

### todo group

#### invariant
  - id must be unique within (item, project, group)
  - description must be unique within (project, group)

```json
group: {
  "id": 123,
  "description": "",
  "displayOrder": 3,
  "projects": [],
}
```