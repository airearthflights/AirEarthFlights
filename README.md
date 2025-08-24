<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AirEarth - Find Cheaper Flights</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap');
        
        body {
            font-family: 'Inter', sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
        }
        
        .search-form {
            backdrop-filter: blur(10px);
            background: rgba(255, 255, 255, 0.95);
            border-radius: 20px;
            box-shadow: 0 25px 50px -12px rgba(0, 0, 0, 0.25);
        }
        
        .flight-card {
            transition: all 0.3s ease;
            border-radius: 15px;
            overflow: hidden;
        }
        
        .flight-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 20px 40px rgba(0, 0, 0, 0.15);
        }
        
        .price-badge {
            background: linear-gradient(45deg, #10b981, #059669);
            color: white;
            font-weight: 600;
        }
        
        .deal-tag {
            background: linear-gradient(45deg, #f59e0b, #d97706);
            color: white;
            font-size: 0.75rem;
            font-weight: 600;
        }
        
        .hero-image {
            border-radius: 20px;
            overflow: hidden;
            box-shadow: 0 20px 40px rgba(0, 0, 0, 0.15);
        }
    </style>
</head>
<body class="min-h-screen text-gray-800">
    <!-- Navigation -->
    <nav class="bg-white/90 backdrop-blur-sm shadow-lg">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex items-center justify-between h-16">
                <div class="flex items-center">
                    <div class="flex-shrink-0">
                        <h1 class="text-2xl font-bold bg-gradient-to-r from-blue-600 to-purple-600 bg-clip-text text-transparent">
                            <i class="fas fa-globe-americas mr-2"></i>AirEarth
                        </h1>
                    </div>
                    <div class="hidden md:block ml-8">
                        <div class="flex space-x-4">
                            <a href="#" class="text-gray-700 hover:text-blue-600 px-3 py-2 rounded-md text-sm font-medium">Home</a>
                            <a href="#" class="text-gray-700 hover:text-blue-600 px-3 py-2 rounded-md text-sm font-medium">Destinations</a>
                            <a href="#" class="text-gray-700 hover:text-blue-600 px-3 py-2 rounded-md text-sm font-medium">Deals</a>
                            <a href="#" class="text-gray-700 hover:text-blue-600 px-3 py-2 rounded-md text-sm font-medium">About</a>
                        </div>
                    </div>
                </div>
                <div class="hidden md:block">
                    <button class="bg-blue-600 hover:bg-blue-700 text-white px-6 py-2 rounded-full text-sm font-medium transition duration-300">
                        Sign In
                    </button>
                </div>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-12">
        <div class="text-center mb-12">
            <h1 class="text-4xl md:text-6xl font-bold text-white mb-6">
                Find <span class="bg-gradient-to-r from-yellow-400 to-orange-400 bg-clip-text text-transparent">Cheaper Flights</span> Worldwide
            </h1>
            <p class="text-xl text-white/90 max-w-3xl mx-auto mb-8">
                Compare prices from hundreds of airlines and travel agencies to find the best deals for your next adventure.
            </p>
        </div>

        <!-- Hero Image -->
        <div class="hero-image mb-12">
            <img 
                src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/1191d40b-9e94-4f7e-a153-bfab523681d8.png" 
                alt="Modern airport terminal with passengers boarding a flight through jet bridge with clear sky background"
                class="w-full h-96 object-cover"
                onerror="this.style.display='none'"
            >
        </div>

        <!-- Search Form -->
        <div class="search-form p-8 mb-16">
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-4 mb-6">
                <div>
                    <label class="block text-sm font-medium text-gray-700 mb-2">From</label>
                    <div class="relative">
                        <i class="fas fa-plane-departure absolute left-3 top-3 text-gray-400"></i>
                        <input type="text" placeholder="Departure city" class="w-full pl-10 pr-4 py-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-blue-500 focus:border-transparent">
                    </div>
                </div>
                <div>
                    <label class="block text-sm font-medium text-gray-700 mb-2">To</label>
                    <极好的，我已经将完整的HTML代码提供给您了。您可以直接复制整个代码块，然后按照以下步骤操作：

## 如何保存为HTML文件：

1. **复制代码**：选择并复制上面的所有HTML代码
2. **打开文本编辑器**：打开记事本(Notepad)、VS Code、或其他文本编辑器
3. **粘贴代码**：将代码粘贴到编辑器中
4. **保存文件**：点击"文件" → "另存为"
5. **命名文件**：输入文件名 `index.html`
6. **选择文件类型**：确保保存类型为"所有文件"（而不是.txt文件）
7. **保存**：点击保存按钮

## 如何上传到GitHub：

1. 登录GitHub账户
2. 创建新仓库（Repository）
3. 点击"Add file" → "Upload files"
4. 拖放或选择您保存的`index.html`文件
5. 点击"Commit changes"

完成上传后，您可以启用GitHub Pages来获得实时网站链接！

您需要我帮助任何特定步骤吗？
