body { 
    font-family: Arial, Helvetica, sans-serif;
    margin:0;
    padding:0;
    background: linear-gradient(to bottom, #f9f9f9, #eef2f3);
    color: #333;
}

header {
    text-align: center;
    padding: 30px;
    background-color: #2c3e50;
    box-shadow: 0 2px 6px rgba(0,0,0,0.15);
    color: white;
}
header img {
    width: 180px;
    height: 180px;
    border-radius: 50%;
    margin-bottom: 10px;
    border: 4px solid #16a085;
}
header h1 {
    margin: 10px 0 5px;
    font-size: 2.2rem;
}
header p {
    margin: 0;
    font-style: italic;
    color: #dfe6e9;
}

section {
    margin: 20px auto;
    max-width: 900px;
    padding: 25px;
    background: #ffffff;
    border-radius: 10px;
    box-shadow: 0 3px 8px rgba(0,0,0,0.08);
}
h1, h2 {
    color: #2c3e50;
    margin-top: 0;
    margin-bottom: 15px;
}

.project {
    width: 200px;
    height: 200px;
    border: 1px solid #ddd;
    margin: 10px;
    text-align: center;
    display: inline-block;
    line-height: 200px;
    border-radius: 10px;
    background: #fafafa;
    transition: transform 0.3s ease, box-shadow 0.3s ease, background 0.3s;
}
.project:hover {
    transform: translateY(-8px);
    box-shadow: 0 6px 16px rgba(0,0,0,0.15);
    background: #16a085; 
    color: white;
}

#bio {
    background-color: #f0f9f9;
    border-left: 5px solid #16a085;
    padding: 20px;
}

footer {
    background-color: #2c3e50;
    text-align: center;
    padding: 15px;
    color: white;
    margin-top: 30px;
}
footer p {
    margin: 0;
    font-size: 0.95rem;
    color: #ecf0f1;
}
