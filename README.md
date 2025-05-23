Program:
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>To Do App</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body class="bg-light">

  <div class="container my-5">
    <h2 class="text-center mb-4">To Do App</h2>

    <div class="input-group mb-4 justify-content-center">
      <input type="text" class="form-control w-50" placeholder="Enter a task here">
      <button class="btn btn-primary ms-2">SAVE</button>
      <button class="btn btn-warning text-white ms-2">GET TASKS</button>
    </div>

    <table class="table table-bordered bg-white">
      <thead class="table-light">
        <tr>
          <th>No.</th>
          <th>Todo item</th>
          <th>Status</th>
          <th>Actions</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>1</td>
          <td>Buy groceries for next week</td>
          <td>In progress</td>
          <td>
            <button class="btn btn-danger btn-sm me-2">DELETE</button>
            <button class="btn btn-success btn-sm">FINISHED</button>
          </td>
        </tr>
        <tr>
          <td>2</td>
          <td>Renew car insurance</td>
          <td>In progress</td>
          <td>
            <button class="btn btn-danger btn-sm me-2">DELETE</button>
            <button class="btn btn-success btn-sm">FINISHED</button>
          </td>
        </tr>
        <tr>
          <td>3</td>
          <td>Sign up for online course</td>
          <td>In progress</td>
          <td>
            <button class="btn btn-danger btn-sm me-2">DELETE</button>
            <button class="btn btn-success btn-sm">FINISHED</button>
          </td>
        </tr>
      </tbody>
    </table>
  </div>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>

```

Output :
![image](https://github.com/user-attachments/assets/96df1135-f44f-421e-adf7-beaed9aa0546)
