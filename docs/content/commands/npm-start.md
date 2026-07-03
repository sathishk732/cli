 * {
  box-sizing: border-box;
}

body {
  margin: 0;
  font-family: Arial, Helvetica, sans-serif;
  background: #f4f7f9;
  color: #1f2933;
}

header {
  background: #075985;
  color: white;
  padding: 24px;
  text-align: center;
}

header h1 {
  margin: 0 0 6px;
  font-size: 28px;
}

header p {
  margin: 0;
  opacity: 0.9;
}

nav {
  background: white;
  padding: 12px 24px;
  display: flex;
  gap: 14px;
  border-bottom: 1px solid #d8e2e8;
  flex-wrap: wrap;
}

nav a {
  color: #075985;
  font-weight: bold;
  text-decoration: none;
}

main {
  max-width: 1100px;
  margin: 24px auto;
  padding: 0 16px;
}

.card, .document-card, .stat {
  background: white;
  border-radius: 14px;
  padding: 20px;
  box-shadow: 0 2px 10px rgba(15, 23, 42, 0.08);
  margin-bottom: 18px;
}

.login-card {
  max-width: 420px;
  margin: 40px auto;
}

.grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(190px, 1fr));
  gap: 16px;
  margin-bottom: 18px;
}

.stat strong {
  display: block;
  font-size: 34px;
  color: #075985;
}

.stat span {
  color: #52616b;
}

label {
  display: block;
  margin-top: 12px;
  font-weight: bold;
}

input, textarea {
  width: 100%;
  padding: 11px;
  margin-top: 6px;
  border: 1px solid #cfd8df;
  border-radius: 8px;
  font-size: 15px;
}

textarea {
  min-height: 95px;
}

button, .button-link {
  display: inline-block;
  margin-top: 14px;
  padding: 10px 14px;
  background: #0284c7;
  color: white;
  border: none;
  border-radius: 8px;
  text-decoration: none;
  font-weight: bold;
  cursor: pointer;
}

.secondary {
  background: #64748b;
}

.actions {
  display: flex;
  align-items: center;
  gap: 10px;
  flex-wrap: wrap;
  margin-top: 10px;
}

.meta, .note {
  color: #64748b;
  font-size: 14px;
}

.signed, .signed-large {
  background: #dcfce7;
  color: #166534;
  padding: 8px 10px;
  border-radius: 999px;
  font-weight: bold;
}

.signed-large {
  display: inline-block;
  border-radius: 8px;
}

.pending {
  background: #fef3c7;
  color: #92400e;
  padding: 8px 10px;
  border-radius: 999px;
  font-weight: bold;
}

.viewer {
  width: 100%;
  height: 720px;
  border: 1px solid #cbd5e1;
  border-radius: 10px;
  margin-top: 16px;
}

.image-viewer {
  width: 100%;
  max-height: 720px;
  object-fit: contain;
  border: 1px solid #cbd5e1;
  border-radius: 10px;
  margin-top: 16px;
}

table {
  width: 100%;
  border-collapse: collapse;
  margin: 16px 0 24px;
  overflow-x: auto;
}

th, td {
  border: 1px solid #d8e2e8;
  padding: 10px;
  text-align: left;
  vertical-align: top;
}

th {
  background: #e0f2fe;
}

hr {
  border: none;
  border-top: 1px solid #d8e2e8;
  margin: 20px 0;
}

@media (max-width: 650px) {
  header h1 {
    font-size: 22px;
  }

  table {
    display: block;
    overflow-x: auto;
  }

  .viewer {
    height: 500px;
  }
}
