<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Data Penjualan Laptop</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 20px;
            background-color: #f5f5f5;
        }
        
        h1 {
            text-align: center;
            color: #333;
            margin-bottom: 30px;
        }
        
        .container {
            max-width: 1000px;
            margin: 0 auto;
            background-color: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        
        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 20px;
        }
        
        th, td {
            padding: 12px 15px;
            text-align: left;
            border-bottom: 1px solid #ddd;
        }
        
        th {
            background-color: #4CAF50;
            color: white;
            font-weight: bold;
        }
        
        tr:nth-child(even) {
            background-color: #f9f9f9;
        }
        
        tr:hover {
            background-color: #f1f1f1;
        }
        
        .diskon {
            color: #e74c3c;
            font-weight: bold;
        }
        
        .total {
            font-weight: bold;
        }
        
        .footer {
            margin-top: 20px;
            text-align: right;
            font-style: italic;
            color: #666;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Data Penjualan Laptop</h1>
        
        <table>
            <thead>
                <tr>
                    <th>No</th>
                    <th>Merk & Model</th>
                    <th>Harga (Rp)</th>
                    <th>Diskon</th>
                    <th>Jumlah</th>
                    <th>Total (Rp)</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>1</td>
                    <td>Asus ROG Zephyrus G14</td>
                    <td>18,999,000</td>
                    <td class="diskon">5%</td>
                    <td>3</td>
                    <td>54,147,150</td>
                </tr>
                <tr>
                    <td>2</td>
                    <td>Dell XPS 13</td>
                    <td>21,500,000</td>
                    <td class="diskon">10%</td>
                    <td>2</td>
                    <td>38,700,000</td>
                </tr>
                <tr>
                    <td>3</td>
                    <td>MacBook Air M1</td>
                    <td>14,999,000</td>
                    <td>0%</td>
                    <td>5</td>
                    <td>74,995,000</td>
                </tr>
                <tr>
                    <td>4</td>
                    <td>Lenovo ThinkPad X1 Carbon</td>
                    <td>22,750,000</td>
                    <td class="diskon">8%</td>
                    <td>1</td>
                    <td>20,930,000</td>
                </tr>
                <tr>
                    <td>5</td>
                    <td>HP Spectre x360</td>
                    <td>19,850,000</td>
                    <td class="diskon">12%</td>
                    <td>2</td>
                    <td>34,936,000</td>
                </tr>
                <tr>
                    <td>6</td>
                    <td>Acer Predator Helios 300</td>
                    <td>16,500,000</td>
                    <td class="diskon">7%</td>
                    <td>4</td>
                    <td>61,380,000</td>
                </tr>
                <tr>
                    <td>7</td>
                    <td>MSI GS66 Stealth</td>
                    <td>25,999,000</td>
                    <td class="diskon">15%</td>
                    <td>1</td>
                    <td>22,099,150</td>
                </tr>
                <tr>
                    <td>8</td>
                    <td>MacBook Pro 14" M1 Pro</td>
                    <td>27,499,000</td>
                    <td>0%</td>
                    <td>2</td>
                    <td>54,998,000</td>
                </tr>
                <tr>
                    <td>9</td>
                    <td>Microsoft Surface Laptop 4</td>
                    <td>17,800,000</td>
                    <td class="diskon">5%</td>
                    <td>3</td>
                    <td>50,730,000</td>
                </tr>
                <tr>
                    <td>10</td>
                    <td>Razer Blade 15</td>
                    <td>30,250,000</td>
                    <td class="diskon">10%</td>
                    <td>1</td>
                    <td>27,225,000</td>
                </tr>
                <tr>
                    <td>11</td>
                    <td>Asus TUF Gaming F15</td>
                    <td>14,200,000</td>
                    <td class="diskon">8%</td>
                    <td>4</td>
                    <td>52,256,000</td>
                </tr>
                <tr>
                    <td>12</td>
                    <td>Lenovo Yoga Slim 7</td>
                    <td>13,750,000</td>
                    <td>0%</td>
                    <td>3</td>
                    <td>41,250,000</td>
                </tr>
                <tr>
                    <td>13</td>
                    <td>Dell Alienware m15 R6</td>
                    <td>28,999,000</td>
                    <td class="diskon">12%</td>
                    <td>1</td>
                    <td>25,519,120</td>
                </tr>
                <tr>
                    <td>14</td>
                    <td>HP Pavilion 15</td>
                    <td>10,500,000</td>
                    <td class="diskon">5%</td>
                    <td>6</td>
                    <td>59,850,000</td>
                </tr>
                <tr>
                    <td>15</td>
                    <td>Acer Swift 3</td>
                    <td>11,200,000</td>
                    <td>0%</td>
                    <td>4</td>
                    <td>44,800,000</td>
                </tr>
            </tbody>
            <tfoot>
                <tr class="total">
                    <td colspan="5">Total Penjualan</td>
                    <td>662,515,420</td>
                </tr>
            </tfoot>
        </table>
        
        <div class="footer">
            Data diperbarui: 1 Agustus 2025
        </div>
    </div>
</body>
</html>
