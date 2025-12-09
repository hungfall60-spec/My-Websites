# Mybody {
  margin: 0;
  font-family: "Poppins", sans-serif;
  background: #eef2f7;
  color: #333;
}

header {
  background: linear-gradient(135deg, #4a90e2, #1e3c72);
  padding: 40px 20px;
  color: #fff;
  text-align: center;
  box-shadow: 0 4px 12px rgba(0,0,0,0.1);
}

nav {
  background: #fff;
  padding: 15px;
  display: flex;
  justify-content: center;
  gap: 30px;
  border-bottom: 2px solid #e2e8f0;
  position: sticky;
  top: 0;
  z-index: 10;
}

nav a {
  color: #1e3c72;
  text-decoration: none;
  font-weight: 600;
  transition: 0.3s;
}

nav a:hover {
  color: #4a90e2;
  transform: scale(1.05);
}

.hero {
  height: 350px;
  background: url('https://images.unsplash.com/photo-1503264116251-35a269479413?auto=format&fit=crop&w=1350&q=80') center/cover;
  display: flex;
  align-items: center;
  justify-content: center;
  color: white;
  font-size: 2.4rem;
  letter-spacing: 1px;
  font-weight: bold;
  text-shadow: 0 4px 10px rgba(0,0,0,0.4);
  animation: fadeIn 1.5s ease-in-out;
}

@keyframes fadeIn {
  from { opacity: 0; }
  to { opacity: 1; }
}

section {
  padding: 40px;
  max-width: 950px;
  margin: 30px auto;
  background: white;
  border-radius: 14px;
  box-shadow: 0 6px 20px rgba(0,0,0,0.07);
  animation: fadeIn 1.2s ease-in-out;
}

h2 {
  color: #1e3c72;
}

footer {
  text-align: center;
  padding: 20px;
  background: #1e3c72;
  color: white;
  margin-top: 30px;
}

.gallery {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  gap: 20px;
}

.gallery img {
  width: 100%;
  border-radius: 10px;
  transition: transform 0.3s, box-shadow 0.3s;
}

.gallery img:hover {
  transform: scale(1.05);
  box-shadow: 0 8px 20px rgba(0,0,0,0.2);
}
-Websites
