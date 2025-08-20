# Automated E-commerce Platform 🛒

A modern, full-stack e-commerce web application with automated cloud infrastructure deployment. This project demonstrates enterprise-level web development practices combined with DevOps automation using Infrastructure as Code.

## 🌟 Features

### Frontend Features
- **Responsive Design**: Mobile-first approach with Bootstrap 4.5
- **Product Management**: Browse products by categories with detailed product pages
- **Shopping Cart**: Add/remove items, quantity management, real-time price calculation
- **Secure Checkout**: Complete checkout process with order confirmation
- **User Interface**: Clean, modern design with intuitive navigation
- **Search Functionality**: Product search with filtering capabilities
- **Contact System**: Contact form with JavaScript validation

### Backend & Infrastructure
- **Infrastructure as Code**: Terraform configuration for AWS resources
- **Automated Deployment**: GitHub Actions CI/CD pipeline
- **Cloud Ready**: Designed for AWS EC2 deployment
- **Scalable Architecture**: Modular design for easy scaling

## 🛠️ Tech Stack

### Frontend
- **HTML5** - Semantic markup
- **CSS3** - Modern styling with custom properties
- **Bootstrap 4.5** - Responsive framework
- **JavaScript** - Interactive functionality and form validation
- **FontAwesome 5.10** - Icon library

### Infrastructure & DevOps
- **Terraform** - Infrastructure as Code
- **AWS EC2** - Cloud computing platform
- **GitHub Actions** - CI/CD automation
- **Git** - Version control

## 📁 Project Structure

```
├── .github/workflows/
│   └── main.yml                 # CI/CD pipeline configuration
├── assets/
│   ├── css/
│   │   └── style.css           # Main stylesheet
│   ├── js/
│   │   └── form.js             # JavaScript functionality
│   └── links/
│       └── links.txt           # External resource links
├── *.html                      # Application pages
├── main.tf                     # Terraform infrastructure configuration
└── README.md                   # Project documentation
```

## 🚀 Getting Started

### Prerequisites
- Web browser (Chrome, Firefox, Safari, Edge)
- Text editor or IDE
- Git
- AWS Account (for deployment)
- Terraform (for infrastructure)

### Local Development

1. **Clone the repository**
   ```bash
   git clone https://github.com/Praveen-1001/Automated-ecommerce-platform.git
   cd automated-ecommerce-platform
   ```

2. **Open locally**
   ```bash
   # Simply open index.html in your browser
   open index.html
   # OR use a local server
   python -m http.server 8000
   ```

3. **Access the application**
   ```
   http://localhost:8000
   ```

### AWS Deployment

1. **Configure AWS credentials**
   ```bash
   aws configure
   ```

2. **Initialize Terraform**
   ```bash
   terraform init
   ```

3. **Plan deployment**
   ```bash
   terraform plan
   ```

4. **Deploy infrastructure**
   ```bash
   terraform apply
   ```

### CI/CD Pipeline

The project includes automated deployment via GitHub Actions:

1. **Setup secrets** in your GitHub repository:
   - `AWS_ACCESS_KEY_ID`
   - `AWS_SECRET_ACCESS_KEY`

2. **Push to main branch** triggers automatic deployment

## 📱 Pages & Features

| Page | Description | Features |
|------|-------------|----------|
| `index.html` | Homepage | Hero carousel, featured products, categories |
| `product.html` | Product listing | Filters, sorting, product grid |
| `product_detail.html` | Product details | Image gallery, specifications, add to cart |
| `category.html` | Product categories | Category browsing, navigation |
| `cart.html` | Shopping cart | Item management, quantity updates, totals |
| `checkout.html` | Checkout process | Billing details, order summary |
| `order_confirmation.html` | Order confirmation | Order details, confirmation number |
| `about.html` | About us | Team information, company mission |
| `contact.html` | Contact form | Contact details, form validation |
| `search.html` | Search results | Product search, filtering |

## 🎨 Design Features

- **Modern UI/UX**: Clean, professional design
- **Mobile Responsive**: Works on all device sizes
- **Interactive Elements**: Hover effects, smooth transitions
- **Accessibility**: Semantic HTML, proper contrast ratios
- **Performance**: Optimized images and CSS

## 🔧 Configuration

### Environment Variables
```bash
# AWS Configuration (for deployment)
AWS_ACCESS_KEY_ID=your_access_key
AWS_SECRET_ACCESS_KEY=your_secret_key
AWS_DEFAULT_REGION=us-east-1
```

### Terraform Variables
```hcl
# main.tf can be customized for different environments
variable "instance_type" {
  default = "t2.micro"
}

variable "region" {
  default = "us-east-1"
}
```



## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 🔗 External Resources

- [Bootstrap 4.5 Documentation](https://getbootstrap.com/docs/4.5/)
- [FontAwesome Icons](https://fontawesome.com/)
- [Terraform AWS Provider](https://registry.terraform.io/providers/hashicorp/aws/latest/docs)
- [GitHub Actions Documentation](https://docs.github.com/en/actions)

## 🚀 Future Enhancements

- [ ] User authentication and registration
- [ ] Payment gateway integration
- [ ] Database integration (MySQL/PostgreSQL)
- [ ] Admin dashboard
- [ ] Email notifications
- [ ] Product reviews and ratings
- [ ] Wishlist functionality
- [ ] Multi-language support

---

**Made with ❤️ by the Development Team**
