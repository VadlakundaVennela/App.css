body {
  margin: 0;
  font-family: Arial, sans-serif;
  background: #f4f6f9;
}

.container {
  width: 95%;
  max-width: 1400px;
  margin: auto;
  padding: 20px;
}

h1 {
  text-align: center;
  color: #333;
}

.employee-form {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 15px;
  background: white;
  padding: 20px;
  border-radius: 10px;
}

.employee-form input,
.search-bar {
  padding: 10px;
  border: 1px solid #ccc;
  border-radius: 5px;
}

.employee-form button,
.view-toggle button,
button {
  padding: 10px;
  border: none;
  background: #007bff;
  color: white;
  cursor: pointer;
  margin: 5px;
  border-radius: 5px;
}

table {
  width: 100%;
  margin-top: 20px;
  border-collapse: collapse;
  background: white;
}

table th,
table td {
  border: 1px solid #ddd;
  padding: 12px;
  text-align: center;
}

table th {
  background: #007bff;
  color: white;
}

.card-container {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 20px;
  margin-top: 20px;
}

.employee-card {
  background: white;
  padding: 20px;
  border-radius: 10px;
}
