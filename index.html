import React, { useState } from 'react';
import { Card, CardContent } from '@/components/ui/card';
import { Button } from '@/components/ui/button';
import { Input } from '@/components/ui/input';
import { ShoppingCart, Star } from 'lucide-react';

const products = [
  { id: 1, name: 'Jumbo shikar', price: 80 },
  { id: 2, name: 'Rajnigandha', price: 200 },
  { id: 3, name: 'Doma', price: 50},
];

export default function Shop() {
  const [cart, setCart] = useState([]);
  const [searchTerm, setSearchTerm] = useState('');

  const addToCart = (product) => {
    setCart((prevCart) => [...prevCart, product]);
  };

  const filteredProducts = products.filter((product) =>
    product.name.toLowerCase().includes(searchTerm.toLowerCase())
  );

  return (
    <div className="min-h-screen bg-gray-100 py-6">
      <div className="container mx-auto px-4">
        <h1 className="text-3xl font-bold text-center mb-6">Welcome To Namgay Buisness</h1>
        <div className="flex justify-between mb-4">
          <Input
            placeholder="Search for products..."
            value={searchTerm}
            onChange={(e) => setSearchTerm(e.target.value)}
            className="w-full max-w-lg"
          />
          <Button variant="outline" className="ml-4">
            <ShoppingCart className="mr-2" /> Cart ({cart.length})
          </Button>
        </div>

        <div className="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-6">
          {filteredProducts.map((product) => (
            <Card key={product.id} className="shadow-lg">
              <img src={product.image} alt={product.name} className="rounded-t-lg" />
              <CardContent>
                <h2 className="text-lg font-semibold">{product.name}</h2>
                <p className="text-gray-600">${product.price.toFixed(2)}</p>
                <div className="flex items-center mb-2">
                  <Star className="text-yellow-500 mr-1" />
                  <span>{product.rating}</span>
                </div>
                <Button onClick={() => addToCart(product)}>Add to Cart</Button>
              </CardContent>
            </Card>
          ))}
        </div>
      </div>
    </div>
  );
}
