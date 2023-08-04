# README.md for Suvage Perfume Product Card
This product card is designed using HTML and CSS to preview a perfume called Suvage. The card includes information about the brand, scent name, gender, available sizes, fragrance notes, description, inspiration, and campaign controversy.
#### Tools Used
- HTML
- CSS
## Basic Structure of HTML
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Suvage Perfume Product Card</title>
    <link rel="stylesheet" href="style.css">
  </head>
  <body>
    <div class="card-container">
      <div class="card">
        <div class="card-image">
          <img src="suvage-perfume.jpg" alt="Suvage Perfume">
        </div>
        <div class="card-content">
          <h2 class="card-title">Sauvage Perfume</h2>
          <ul class="card-details">
            <li><strong>Brand:</strong> Christian Dior</li>
            <li><strong>Scent name:</strong> Sauvage</li>
            <li><strong>Gender:</strong> Men's</li>
            <li><strong>Available sizes:</strong> 3.4 oz, 6.8 oz</li>
            <li><strong>Fragrance notes:</strong>
              <ul>
                <li>Top notes: Calabrian Bergamot</li>
                <li>Heart notes: Sandalwood</li>
                <li>Base notes: Olibanum, Tonka bean, Vanilla</li>
              </ul>
            </li>
            <li><strong>Description:</strong> Sauvage is a captivating men's perfume that combines the freshness of juicy, spicy Calabrian Bergamot with the sensuality of mysterious Papua New Guinean Vanilla.</li>
            <li><strong>Inspiration:</strong> The fragrance is inspired by wide-open spaces and the white-hot desert landscape under a bright blue sky.</li>
            <li><strong>Campaign Controversy:</strong> The Sauvage perfume campaign featuring Johnny Depp has faced criticism for its use of Indigenous imagery, with accusations of cultural appropriation.</li>
          </ul>
        </div>
      </div>
    </div>
  </body>
</html>
```
## CSS Styling
```css
.card-container {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
}

.card {
  width: 400px;
  background-color: #fff;
  box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.2);
  border-radius: 10px;
  overflow: hidden;
}

.card-image img {
  width: 100%;
  height: auto;
}

.card-content {
  padding: 20px;
}

.card-title {
  font-size: 24px;
  margin: 0 0 10px;
}

.card-details {
  list-style: none;
  padding: 0;
  margin: 0;
}

.card-details li {
  margin-bottom: 10px;
}

.card-details li strong {
  font-weight: bold;
  margin-right: 5px;
}
```
Suvage Perfume Product Card Preview
