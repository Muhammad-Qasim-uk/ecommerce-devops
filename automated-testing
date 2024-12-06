from django.test import TestCase
from .models import Product

class ProductModelTest(TestCase):
    def test_create_product(self):
        product = Product.objects.create(
            name="Test Product",
            description="Test Description",
            price=10.99,
            stock=100
        )
        self.assertEqual(product.name, "Test Product")
