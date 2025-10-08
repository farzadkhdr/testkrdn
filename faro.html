<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Car Rental System</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        :root {
            --primary-color: #3498db;
            --secondary-color: #2c3e50;
            --success-color: #27ae60;
            --danger-color: #e74c3c;
            --warning-color: #f39c12;
            --info-color: #17a2b8;
        }
        
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #f8f9fa;
            margin: 0;
            padding: 0;
        }
        
        /* Login Screen Styles */
        #loginScreen {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            padding: 20px;
        }
        
        .login-container {
            background: white;
            border-radius: 15px;
            box-shadow: 0 15px 35px rgba(0,0,0,0.1);
            overflow: hidden;
            max-width: 400px;
            width: 100%;
        }
        
        .login-header {
            background: var(--secondary-color);
            color: white;
            padding: 30px 20px;
            text-align: center;
        }
        
        .login-body {
            padding: 30px;
        }
        
        .form-control {
            border-radius: 8px;
            padding: 12px 15px;
            border: 2px solid #e9ecef;
            transition: all 0.3s;
        }
        
        .form-control:focus {
            border-color: var(--primary-color);
            box-shadow: 0 0 0 0.2rem rgba(52, 152, 219, 0.25);
        }
        
        .btn-login {
            background: var(--primary-color);
            border: none;
            padding: 12px;
            border-radius: 8px;
            font-weight: 600;
            transition: all 0.3s;
            color: white;
            width: 100%;
        }
        
        .btn-login:hover {
            background: #2980b9;
            transform: translateY(-2px);
        }
        
        .default-info {
            background: #f8f9fa;
            border-radius: 8px;
            padding: 15px;
            margin-top: 20px;
            font-size: 0.9rem;
        }
        
        /* Main App Styles */
        #mainApp {
            display: none;
        }
        
        .navbar-brand {
            font-weight: bold;
        }
        
        .sidebar {
            background-color: var(--secondary-color);
            color: white;
            min-height: calc(100vh - 56px);
            padding: 0;
            position: fixed;
            width: 250px;
        }
        
        .sidebar .nav-link {
            color: rgba(255, 255, 255, 0.8);
            padding: 12px 20px;
            border-bottom: 1px solid rgba(255, 255, 255, 0.1);
            transition: all 0.3s;
        }
        
        .sidebar .nav-link:hover, .sidebar .nav-link.active {
            background-color: rgba(255, 255, 255, 0.1);
            color: white;
        }
        
        .sidebar .nav-link i {
            margin-right: 10px;
            width: 20px;
            text-align: center;
        }
        
        .main-content {
            margin-left: 250px;
            padding: 20px;
        }
        
        .card {
            border: none;
            box-shadow: 0 0.125rem 0.25rem rgba(0, 0, 0, 0.075);
            margin-bottom: 20px;
            border-radius: 10px;
        }
        
        .card-header {
            background-color: white;
            border-bottom: 1px solid rgba(0, 0, 0, 0.125);
            font-weight: 600;
            border-radius: 10px 10px 0 0 !important;
        }
        
        .dashboard-card {
            transition: transform 0.3s;
            border-left: 4px solid var(--primary-color);
        }
        
        .dashboard-card:hover {
            transform: translateY(-5px);
        }
        
        .table-responsive {
            border-radius: 5px;
        }
        
        .tab-content {
            padding: 20px;
            background-color: white;
            border-radius: 0 0 10px 10px;
        }
        
        .nav-tabs .nav-link.active {
            border-bottom: 3px solid var(--primary-color);
            font-weight: 600;
        }
        
        .btn-primary {
            background-color: var(--primary-color);
            border-color: var(--primary-color);
        }
        
        .btn-success {
            background-color: var(--success-color);
            border-color: var(--success-color);
        }
        
        .btn-danger {
            background-color: var(--danger-color);
            border-color: var(--danger-color);
        }
        
        .btn-warning {
            background-color: var(--warning-color);
            border-color: var(--warning-color);
        }
        
        .logo-container {
            display: flex;
            align-items: center;
            justify-content: center;
            padding: 15px;
            border-bottom: 1px solid rgba(255, 255, 255, 0.1);
        }
        
        .system-name {
            font-size: 1.2rem;
            font-weight: bold;
            margin-left: 10px;
        }
        
        .copyright {
            position: absolute;
            bottom: 10px;
            width: 100%;
            text-align: center;
            font-size: 0.8rem;
            color: rgba(255, 255, 255, 0.6);
        }
        
        .print-only {
            display: none;
        }
        
        @media print {
            .no-print {
                display: none !important;
            }
            .print-only {
                display: block;
            }
            body {
                background-color: white;
            }
            .card {
                box-shadow: none;
                border: 1px solid #ddd;
            }
        }
        
        .vehicle-details, .customer-details {
            display: none;
            margin-top: 20px;
        }
        
        .suggestion-list {
            position: absolute;
            background: white;
            border: 1px solid #ddd;
            max-height: 200px;
            overflow-y: auto;
            z-index: 1000;
            width: 100%;
            display: none;
            border-radius: 0 0 5px 5px;
        }
        
        .suggestion-item {
            padding: 8px 12px;
            cursor: pointer;
            border-bottom: 1px solid #f0f0f0;
        }
        
        .suggestion-item:hover {
            background-color: #f8f9fa;
        }
        
        .status-returned {
            background-color: #d4edda;
        }
        
        .status-not-returned {
            background-color: #f8d7da;
        }
        
        .invoice-logo {
            text-align: center;
            margin-bottom: 20px;
        }
        
        .invoice-logo img {
            max-width: 150px;
            height: auto;
        }
        
        .admin-only {
            display: none;
        }
        
        .user-restricted {
            display: none;
        }
        
        /* Responsive Design */
        @media (max-width: 768px) {
            .sidebar {
                position: relative;
                width: 100%;
                min-height: auto;
            }
            
            .main-content {
                margin-left: 0;
            }
            
            .copyright {
                position: relative;
                margin-top: 20px;
            }
        }
    </style>
</head>
<body>
    <!-- Login Screen -->
    <div id="loginScreen">
        <div class="login-container">
            <div class="login-header">
                <i class="fas fa-car fa-3x mb-3"></i>
                <h2>Car Rental System</h2>
                <p class="mb-0">Login to Access Dashboard</p>
            </div>
            
            <div class="login-body">
                <form id="loginForm">
                    <div class="mb-3">
                        <label for="username" class="form-label">Username</label>
                        <input type="text" class="form-control" id="username" placeholder="Enter username" required>
                    </div>
                    
                    <div class="mb-3">
                        <label for="password" class="form-label">Password</label>
                        <input type="password" class="form-control" id="password" placeholder="Enter password" required>
                    </div>
                    
                    <button type="submit" class="btn btn-login">
                        <i class="fas fa-sign-in-alt me-2"></i>Login
                    </button>
                </form>
                
                <div class="default-info">
                    <h6><i class="fas fa-info-circle me-2"></i>Default Login:</h6>
                    <div class="row">
                        <div class="col-6">
                            <strong>Username:</strong> admin
                        </div>
                        <div class="col-6">
                            <strong>Password:</strong> 000000
                        </div>
                    </div>
                </div>
                
                <div class="text-center mt-4">
                    <small class="text-muted">Created by Farzad Programmer - Not Editable</small>
                </div>
            </div>
        </div>
    </div>

    <!-- Main Application -->
    <div id="mainApp">
        <!-- Navigation Bar -->
        <nav class="navbar navbar-expand-lg navbar-dark bg-dark no-print">
            <div class="container-fluid">
                <a class="navbar-brand" href="#">
                    <i class="fas fa-car"></i> Car Rental System
                </a>
                <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                    <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse" id="navbarNav">
                    <ul class="navbar-nav ms-auto">
                        <li class="nav-item dropdown">
                            <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-bs-toggle="dropdown">
                                <i class="fas fa-user-circle"></i> <span id="currentUser">Admin</span>
                            </a>
                            <ul class="dropdown-menu">
                                <li class="admin-only"><a class="dropdown-item" href="#" data-bs-toggle="modal" data-bs-target="#changePasswordModal"><i class="fas fa-key"></i> Change Password</a></li>
                                <li class="admin-only"><a class="dropdown-item" href="#" data-bs-toggle="modal" data-bs-target="#userManagementModal"><i class="fas fa-users"></i> User Management</a></li>
                                <li><hr class="dropdown-divider"></li>
                                <li><a class="dropdown-item" href="#" id="logoutBtn"><i class="fas fa-sign-out-alt"></i> Logout</a></li>
                            </ul>
                        </li>
                    </ul>
                </div>
            </div>
        </nav>

        <div class="container-fluid">
            <div class="row">
                <!-- Sidebar -->
                <div class="col-md-2 sidebar d-none d-md-block no-print">
                    <div class="logo-container">
                        <i class="fas fa-car-side fa-2x text-primary"></i>
                        <span class="system-name">RentalSys</span>
                    </div>
                    <ul class="nav flex-column">
                        <li class="nav-item">
                            <a class="nav-link active" href="#dashboard" data-bs-toggle="tab">
                                <i class="fas fa-tachometer-alt"></i> Dashboard
                            </a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#vehicles" data-bs-toggle="tab">
                                <i class="fas fa-car"></i> Vehicles
                            </a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#customers" data-bs-toggle="tab">
                                <i class="fas fa-users"></i> Customers
                            </a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#rentals" data-bs-toggle="tab">
                                <i class="fas fa-receipt"></i> Rentals
                            </a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#returns" data-bs-toggle="tab">
                                <i class="fas fa-undo"></i> Vehicle Returns
                            </a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#debts" data-bs-toggle="tab">
                                <i class="fas fa-money-bill-wave"></i> Debts & Payments
                            </a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#fines" data-bs-toggle="tab">
                                <i class="fas fa-gavel"></i> Fines & Taxes
                            </a>
                        </li>
                        <li class="nav-item admin-only">
                            <a class="nav-link" href="#reports" data-bs-toggle="tab">
                                <i class="fas fa-chart-bar"></i> Reports
                            </a>
                        </li>
                        <li class="nav-item admin-only">
                            <a class="nav-link" href="#settings" data-bs-toggle="tab">
                                <i class="fas fa-cogs"></i> System Settings
                            </a>
                        </li>
                    </ul>
                    <div class="copyright">
                        Created by Farzad Programmer<br>Not Editable
                    </div>
                </div>

                <!-- Main Content -->
                <div class="col-md-10 main-content">
                    <div class="tab-content mt-4">
                        <!-- Dashboard Tab -->
                        <div class="tab-pane fade show active" id="dashboard">
                            <h2 class="mb-4">Dashboard</h2>
                            <div class="row" id="dashboardStats">
                                <!-- Dashboard statistics will be loaded here -->
                            </div>
                            
                            <div class="row">
                                <div class="col-md-6">
                                    <div class="card">
                                        <div class="card-header">
                                            Recent Rentals
                                        </div>
                                        <div class="card-body">
                                            <div class="table-responsive">
                                                <table class="table table-hover">
                                                    <thead>
                                                        <tr>
                                                            <th>Customer</th>
                                                            <th>Vehicle</th>
                                                            <th>Date</th>
                                                            <th>Amount</th>
                                                            <th>Status</th>
                                                        </tr>
                                                    </thead>
                                                    <tbody id="recentRentalsTable">
                                                        <!-- Recent rentals will be loaded here -->
                                                    </tbody>
                                                </table>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                                <div class="col-md-6">
                                    <div class="card">
                                        <div class="card-header">
                                            Vehicle Status
                                        </div>
                                        <div class="card-body">
                                            <canvas id="vehicleStatusChart" width="400" height="200"></canvas>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>

                        <!-- Vehicles Tab -->
                        <div class="tab-pane fade" id="vehicles">
                            <h2 class="mb-4">Vehicle Management</h2>
                            
                            <ul class="nav nav-tabs mb-3">
                                <li class="nav-item">
                                    <a class="nav-link active" data-bs-toggle="tab" href="#addVehicle">Add Vehicle</a>
                                </li>
                                <li class="nav-item">
                                    <a class="nav-link" data-bs-toggle="tab" href="#vehicleList">Vehicle List</a>
                                </li>
                                <li class="nav-item admin-only">
                                    <a class="nav-link" data-bs-toggle="tab" href="#vehicleHistory">Vehicle History</a>
                                </li>
                            </ul>
                            
                            <div class="tab-content">
                                <div class="tab-pane fade show active" id="addVehicle">
                                    <div class="card">
                                        <div class="card-header">
                                            Add New Vehicle
                                        </div>
                                        <div class="card-body">
                                            <form id="addVehicleForm">
                                                <div class="row">
                                                    <div class="col-md-6 mb-3">
                                                        <label for="vehicleName" class="form-label">Vehicle Name</label>
                                                        <input type="text" class="form-control" id="vehicleName" required>
                                                    </div>
                                                    <div class="col-md-6 mb-3">
                                                        <label for="vehicleOdometer" class="form-label">Odometer</label>
                                                        <input type="number" class="form-control" id="vehicleOdometer" required>
                                                    </div>
                                                </div>
                                                <div class="row">
                                                    <div class="col-md-6 mb-3">
                                                        <label for="vehicleVin" class="form-label">VIN #</label>
                                                        <input type="text" class="form-control" id="vehicleVin" required>
                                                    </div>
                                                    <div class="col-md-6 mb-3">
                                                        <label for="vehiclePlate" class="form-label">Plate Number</label>
                                                        <input type="text" class="form-control" id="vehiclePlate" required>
                                                    </div>
                                                </div>
                                                <div class="row">
                                                    <div class="col-md-6 mb-3">
                                                        <label for="vehicleColor" class="form-label">Color</label>
                                                        <input type="text" class="form-control" id="vehicleColor" required>
                                                    </div>
                                                    <div class="col-md-6 mb-3">
                                                        <label for="vehicleModel" class="form-label">Model</label>
                                                        <input type="text" class="form-control" id="vehicleModel" required>
                                                    </div>
                                                </div>
                                                <button type="submit" class="btn btn-primary">Add Vehicle</button>
                                            </form>
                                        </div>
                                    </div>
                                </div>
                                
                                <div class="tab-pane fade" id="vehicleList">
                                    <div class="card">
                                        <div class="card-header d-flex justify-content-between align-items-center">
                                            <span>Vehicle List</span>
                                            <div class="input-group" style="width: 300px;">
                                                <input type="text" class="form-control" id="vehicleSearch" placeholder="Search vehicles...">
                                                <button class="btn btn-outline-secondary" type="button" id="vehicleSearchBtn">
                                                    <i class="fas fa-search"></i>
                                                </button>
                                            </div>
                                        </div>
                                        <div class="card-body">
                                            <div class="table-responsive">
                                                <table class="table table-hover">
                                                    <thead>
                                                        <tr>
                                                            <th>Name</th>
                                                            <th>Model</th>
                                                            <th>Color</th>
                                                            <th>Plate #</th>
                                                            <th>Odometer</th>
                                                            <th>Status</th>
                                                            <th>Actions</th>
                                                        </tr>
                                                    </thead>
                                                    <tbody id="vehicleTableBody">
                                                        <!-- Vehicle data will be populated here -->
                                                    </tbody>
                                                </table>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                                
                                <div class="tab-pane fade admin-only" id="vehicleHistory">
                                    <div class="card">
                                        <div class="card-header">
                                            Vehicle Rental History
                                        </div>
                                        <div class="card-body">
                                            <div class="table-responsive">
                                                <table class="table table-hover">
                                                    <thead>
                                                        <tr>
                                                            <th>Vehicle</th>
                                                            <th>Customer</th>
                                                            <th>Rental Date</th>
                                                            <th>Return Date</th>
                                                            <th>Amount</th>
                                                            <th>Status</th>
                                                        </tr>
                                                    </thead>
                                                    <tbody id="vehicleHistoryTableBody">
                                                        <!-- Vehicle history will be populated here -->
                                                    </tbody>
                                                </table>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>

                        <!-- Customers Tab -->
                        <div class="tab-pane fade" id="customers">
                            <h2 class="mb-4">Customer Management</h2>
                            
                            <ul class="nav nav-tabs mb-3">
                                <li class="nav-item">
                                    <a class="nav-link active" data-bs-toggle="tab" href="#addCustomer">Add Customer</a>
                                </li>
                                <li class="nav-item">
                                    <a class="nav-link" data-bs-toggle="tab" href="#customerList">Customer List</a>
                                </li>
                            </ul>
                            
                            <div class="tab-content">
                                <div class="tab-pane fade show active" id="addCustomer">
                                    <div class="card">
                                        <div class="card-header">
                                            Add New Customer
                                        </div>
                                        <div class="card-body">
                                            <form id="addCustomerForm">
                                                <div class="row">
                                                    <div class="col-md-6 mb-3">
                                                        <label for="customerFullName" class="form-label">Full Name</label>
                                                        <input type="text" class="form-control" id="customerFullName" required>
                                                    </div>
                                                    <div class="col-md-6 mb-3">
                                                        <label for="customerAge" class="form-label">Age</label>
                                                        <input type="number" class="form-control" id="customerAge" required>
                                                    </div>
                                                </div>
                                                <div class="row">
                                                    <div class="col-md-6 mb-3">
                                                        <label for="customerId" class="form-label">PS/ID</label>
                                                        <input type="text" class="form-control" id="customerId" required>
                                                    </div>
                                                    <div class="col-md-6 mb-3">
                                                        <label for="customerNationality" class="form-label">Nationality</label>
                                                        <input type="text" class="form-control" id="customerNationality" required>
                                                    </div>
                                                </div>
                                                <div class="row">
                                                    <div class="col-md-6 mb-3">
                                                        <label for="customerContact" class="form-label">Contact Number</label>
                                                        <input type="text" class="form-control" id="customerContact" required>
                                                    </div>
                                                    <div class="col-md-6 mb-3">
                                                        <label for="customerAddress" class="form-label">Address</label>
                                                        <input type="text" class="form-control" id="customerAddress" required>
                                                    </div>
                                                </div>
                                                <div class="mb-3">
                                                    <label for="guaranteeDoc" class="form-label">Guarantee / Document</label>
                                                    <input type="file" class="form-control" id="guaranteeDoc">
                                                </div>
                                                <button type="submit" class="btn btn-primary">Add Customer</button>
                                            </form>
                                        </div>
                                    </div>
                                </div>
                                
                                <div class="tab-pane fade" id="customerList">
                                    <div class="card">
                                        <div class="card-header d-flex justify-content-between align-items-center">
                                            <span>Customer List</span>
                                            <div class="input-group" style="width: 300px;">
                                                <input type="text" class="form-control" id="customerSearch" placeholder="Search customers...">
                                                <button class="btn btn-outline-secondary" type="button" id="customerSearchBtn">
                                                    <i class="fas fa-search"></i>
                                                </button>
                                            </div>
                                        </div>
                                        <div class="card-body">
                                            <div class="table-responsive">
                                                <table class="table table-hover">
                                                    <thead>
                                                        <tr>
                                                            <th>Full Name</th>
                                                            <th>Age</th>
                                                            <th>ID</th>
                                                            <th>Nationality</th>
                                                            <th>Contact</th>
                                                            <th>Total Debt</th>
                                                            <th>Actions</th>
                                                        </tr>
                                                    </thead>
                                                    <tbody id="customerTableBody">
                                                        <!-- Customer data will be populated here -->
                                                    </tbody>
                                                </table>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>

                        <!-- Rentals Tab -->
                        <div class="tab-pane fade" id="rentals">
                            <h2 class="mb-4">Rental Management</h2>
                            
                            <div class="card">
                                <div class="card-header">
                                    Create New Rental
                                </div>
                                <div class="card-body">
                                    <form id="createRentalForm">
                                        <div class="row">
                                            <div class="col-md-6 mb-3">
                                                <label for="rentalCustomer" class="form-label">Customer</label>
                                                <input type="text" class="form-control" id="rentalCustomer" placeholder="Search customer...">
                                                <div class="suggestion-list" id="customerSuggestions"></div>
                                            </div>
                                            <div class="col-md-6 mb-3">
                                                <label for="rentalVehicle" class="form-label">Vehicle</label>
                                                <input type="text" class="form-control" id="rentalVehicle" placeholder="Search vehicle...">
                                                <div class="suggestion-list" id="vehicleSuggestions"></div>
                                            </div>
                                        </div>
                                        <div class="row">
                                            <div class="col-md-6 mb-3">
                                                <label for="rentalAmount" class="form-label">Rental Amount</label>
                                                <input type="number" class="form-control" id="rentalAmount" required>
                                            </div>
                                            <div class="col-md-6 mb-3">
                                                <label for="rentalDays" class="form-label">Rental Days</label>
                                                <input type="number" class="form-control" id="rentalDays" required>
                                            </div>
                                        </div>
                                        <div class="row">
                                            <div class="col-md-6 mb-3">
                                                <label for="invoiceCode" class="form-label">Invoice Code</label>
                                                <input type="text" class="form-control" id="invoiceCode">
                                            </div>
                                        </div>
                                        <button type="submit" class="btn btn-primary">Create Rental</button>
                                    </form>
                                </div>
                            </div>
                            
                            <div class="card mt-4">
                                <div class="card-header d-flex justify-content-between align-items-center">
                                    <span>Rental History</span>
                                    <div class="input-group" style="width: 300px;">
                                        <input type="text" class="form-control" id="rentalSearch" placeholder="Search by invoice code...">
                                        <button class="btn btn-outline-secondary" type="button" id="rentalSearchBtn">
                                            <i class="fas fa-search"></i>
                                        </button>
                                    </div>
                                </div>
                                <div class="card-body">
                                    <div class="table-responsive">
                                        <table class="table table-hover">
                                            <thead>
                                                <tr>
                                                    <th>Invoice Code</th>
                                                    <th>Customer</th>
                                                    <th>Vehicle</th>
                                                    <th>Date</th>
                                                    <th>Amount</th>
                                                    <th>Status</th>
                                                    <th>Actions</th>
                                                </tr>
                                            </thead>
                                            <tbody id="rentalTableBody">
                                                <!-- Rental data will be populated here -->
                                            </tbody>
                                        </table>
                                    </div>
                                </div>
                            </div>
                        </div>

                        <!-- Vehicle Returns Tab -->
                        <div class="tab-pane fade" id="returns">
                            <h2 class="mb-4">Vehicle Returns</h2>
                            
                            <div class="card">
                                <div class="card-header">
                                    Return Vehicle
                                </div>
                                <div class="card-body">
                                    <form id="returnVehicleForm">
                                        <div class="row">
                                            <div class="col-md-6 mb-3">
                                                <label for="returnInvoice" class="form-label">Invoice Code</label>
                                                <input type="text" class="form-control" id="returnInvoice" placeholder="Search invoice...">
                                                <div class="suggestion-list" id="returnInvoiceSuggestions"></div>
                                            </div>
                                            <div class="col-md-6 mb-3">
                                                <label for="fineAmount" class="form-label">Fine Amount (if any)</label>
                                                <input type="number" class="form-control" id="fineAmount" value="0">
                                            </div>
                                        </div>
                                        <button type="submit" class="btn btn-primary">Return Vehicle</button>
                                    </form>
                                </div>
                            </div>
                            
                            <div class="card mt-4">
                                <div class="card-header">
                                    Return History
                                </div>
                                <div class="card-body">
                                    <div class="table-responsive">
                                        <table class="table table-hover">
                                            <thead>
                                                <tr>
                                                    <th>Invoice Code</th>
                                                    <th>Customer</th>
                                                    <th>Vehicle</th>
                                                    <th>Return Date</th>
                                                    <th>Fine</th>
                                                    <th>Total</th>
                                                </tr>
                                            </thead>
                                            <tbody id="returnTableBody">
                                                <!-- Return data will be populated here -->
                                            </tbody>
                                        </table>
                                    </div>
                                </div>
                            </div>
                        </div>

                        <!-- Debts & Payments Tab -->
                        <div class="tab-pane fade" id="debts">
                            <h2 class="mb-4">Debts & Payments</h2>
                            
                            <div class="card">
                                <div class="card-header">
                                    Search Customer
                                </div>
                                <div class="card-body">
                                    <div class="row">
                                        <div class="col-md-6 mb-3">
                                            <label for="debtCustomer" class="form-label">Customer</label>
                                            <input type="text" class="form-control" id="debtCustomer" placeholder="Search customer...">
                                            <div class="suggestion-list" id="debtCustomerSuggestions"></div>
                                        </div>
                                        <div class="col-md-6 mb-3">
                                            <label class="form-label">Current Debt</label>
                                            <div class="form-control" id="currentDebt">$0</div>
                                        </div>
                                    </div>
                                    <div class="row mt-3">
                                        <div class="col-12">
                                            <h6>Customer Summary</h6>
                                            <div id="customerDebtSummary">
                                                <!-- Customer debt summary will be populated here -->
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                            
                            <div class="card mt-4">
                                <div class="card-header">
                                    Add Payment
                                </div>
                                <div class="card-body">
                                    <form id="addPaymentForm">
                                        <div class="row">
                                            <div class="col-md-6 mb-3">
                                                <label for="paymentAmount" class="form-label">Payment Amount</label>
                                                <input type="number" class="form-control" id="paymentAmount" required>
                                            </div>
                                            <div class="col-md-6 mb-3">
                                                <label for="paymentDate" class="form-label">Date</label>
                                                <input type="date" class="form-control" id="paymentDate" required>
                                            </div>
                                        </div>
                                        <button type="submit" class="btn btn-primary">Add Payment</button>
                                    </form>
                                </div>
                            </div>
                            
                            <div class="card mt-4">
                                <div class="card-header">
                                    Payment History
                                </div>
                                <div class="card-body">
                                    <div class="table-responsive">
                                        <table class="table table-hover">
                                            <thead>
                                                <tr>
                                                    <th>Date</th>
                                                    <th>Customer</th>
                                                    <th>Amount</th>
                                                    <th>Actions</th>
                                                </tr>
                                            </thead>
                                            <tbody id="paymentTableBody">
                                                <!-- Payment data will be populated here -->
                                            </tbody>
                                        </table>
                                    </div>
                                </div>
                            </div>
                        </div>

                        <!-- Fines & Taxes Tab -->
                        <div class="tab-pane fade" id="fines">
                            <h2 class="mb-4">Fines & Taxes</h2>
                            
                            <div class="card">
                                <div class="card-header">
                                    Add Fine/Tax
                                </div>
                                <div class="card-body">
                                    <form id="addFineTaxForm">
                                        <div class="row">
                                            <div class="col-md-6 mb-3">
                                                <label for="fineTaxType" class="form-label">Type</label>
                                                <select class="form-select" id="fineTaxType" required>
                                                    <option value="">Select Type</option>
                                                    <option value="fine">Fine</option>
                                                    <option value="tax">Tax</option>
                                                </select>
                                            </div>
                                            <div class="col-md-6 mb-3">
                                                <label for="fineTaxAmount" class="form-label">Amount</label>
                                                <input type="number" class="form-control" id="fineTaxAmount" required>
                                            </div>
                                        </div>
                                        <div class="row">
                                            <div class="col-md-6 mb-3">
                                                <label for="fineTaxInvoice" class="form-label">Invoice Code</label>
                                                <input type="text" class="form-control" id="fineTaxInvoice" placeholder="Search invoice...">
                                                <div class="suggestion-list" id="invoiceSuggestions"></div>
                                            </div>
                                        </div>
                                        <button type="submit" class="btn btn-primary">Add Fine/Tax</button>
                                    </form>
                                </div>
                            </div>
                            
                            <div class="card mt-4">
                                <div class="card-header">
                                    Fines & Taxes History
                                </div>
                                <div class="card-body">
                                    <div class="table-responsive">
                                        <table class="table table-hover">
                                            <thead>
                                                <tr>
                                                    <th>Date</th>
                                                    <th>Type</th>
                                                    <th>Amount</th>
                                                    <th>Invoice</th>
                                                    <th>Actions</th>
                                                </tr>
                                            </thead>
                                            <tbody id="fineTaxTableBody">
                                                <!-- Fine/Tax data will be populated here -->
                                            </tbody>
                                        </table>
                                    </div>
                                </div>
                            </div>
                        </div>

                        <!-- Reports Tab -->
                        <div class="tab-pane fade admin-only" id="reports">
                            <h2 class="mb-4">Reports</h2>
                            
                            <div class="card">
                                <div class="card-header">
                                    Generate Report
                                </div>
                                <div class="card-body">
                                    <form id="generateReportForm">
                                        <div class="row">
                                            <div class="col-md-4 mb-3">
                                                <label for="reportStartDate" class="form-label">Start Date</label>
                                                <input type="date" class="form-control" id="reportStartDate" required>
                                            </div>
                                            <div class="col-md-4 mb-3">
                                                <label for="reportEndDate" class="form-label">End Date</label>
                                                <input type="date" class="form-control" id="reportEndDate" required>
                                            </div>
                                            <div class="col-md-4 mb-3">
                                                <label for="reportType" class="form-label">Report Type</label>
                                                <select class="form-select" id="reportType" required>
                                                    <option value="rentals">Rentals</option>
                                                    <option value="payments">Payments</option>
                                                    <option value="fines">Fines & Taxes</option>
                                                    <option value="returns">Vehicle Returns</option>
                                                </select>
                                            </div>
                                        </div>
                                        <div class="row">
                                            <div class="col-md-6 mb-3">
                                                <label for="reportVehicle" class="form-label">Vehicle (Optional)</label>
                                                <input type="text" class="form-control" id="reportVehicle" placeholder="Vehicle name or plate">
                                            </div>
                                            <div class="col-md-6 mb-3">
                                                <label for="reportFormat" class="form-label">Output Format</label>
                                                <select class="form-select" id="reportFormat" required>
                                                    <option value="csv">CSV</option>
                                                    <option value="print">Print</option>
                                                </select>
                                            </div>
                                        </div>
                                        <button type="submit" class="btn btn-primary">Generate Report</button>
                                    </form>
                                </div>
                            </div>
                            
                            <div class="card mt-4" id="reportResultsCard" style="display: none;">
                                <div class="card-header d-flex justify-content-between align-items-center">
                                    <span id="reportTitle">Report Results</span>
                                    <div>
                                        <button class="btn btn-success" id="exportReportBtn">
                                            <i class="fas fa-download"></i> Export as CSV
                                        </button>
                                        <button class="btn btn-primary" id="printReportBtn">
                                            <i class="fas fa-print"></i> Print Report
                                        </button>
                                    </div>
                                </div>
                                <div class="card-body">
                                    <div class="table-responsive">
                                        <table class="table table-hover" id="reportResultsTable">
                                            <thead id="reportResultsHead">
                                                <!-- Table headers will be populated here -->
                                            </thead>
                                            <tbody id="reportResultsBody">
                                                <!-- Report results will be populated here -->
                                            </tbody>
                                        </table>
                                    </div>
                                </div>
                            </div>
                        </div>

                        <!-- System Settings Tab -->
                        <div class="tab-pane fade admin-only" id="settings">
                            <h2 class="mb-4">System Settings</h2>
                            
                            <div class="card">
                                <div class="card-header">
                                    System Configuration
                                </div>
                                <div class="card-body">
                                    <form id="systemSettingsForm">
                                        <div class="row">
                                            <div class="col-md-6 mb-3">
                                                <label for="systemName" class="form-label">System Name</label>
                                                <input type="text" class="form-control" id="systemName" value="Car Rental System" required>
                                            </div>
                                            <div class="col-md-6 mb-3">
                                                <label for="systemLogo" class="form-label">System Logo</label>
                                                <input type="file" class="form-control" id="systemLogo" accept="image/*">
                                            </div>
                                        </div>
                                        <div class="row">
                                            <div class="col-md-12 mb-3">
                                                <label for="systemMessage" class="form-label">System Message</label>
                                                <textarea class="form-control" id="systemMessage" rows="3"></textarea>
                                            </div>
                                        </div>
                                        <div class="row">
                                            <div class="col-md-6 mb-3">
                                                <label for="backupFrequency" class="form-label">Backup Frequency</label>
                                                <select class="form-select" id="backupFrequency" required>
                                                    <option value="daily">Daily</option>
                                                    <option value="weekly">Weekly</option>
                                                    <option value="monthly">Monthly</option>
                                                </select>
                                            </div>
                                        </div>
                                        <div class="row">
                                            <div class="col-md-6 mb-3">
                                                <button type="button" class="btn btn-success w-100" id="backupBtn">
                                                    <i class="fas fa-download"></i> Backup Now
                                                </button>
                                            </div>
                                            <div class="col-md-6 mb-3">
                                                <button type="button" class="btn btn-info w-100" id="restoreBtn">
                                                    <i class="fas fa-upload"></i> Restore Backup
                                                </button>
                                            </div>
                                        </div>
                                        <button type="submit" class="btn btn-primary">Save Settings</button>
                                    </form>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <!-- Modals -->
    <div class="modal fade" id="changePasswordModal" tabindex="-1">
        <div class="modal-dialog">
            <div class="modal-content">
                <div class="modal-header">
                    <h5 class="modal-title">Change Password</h5>
                    <button type="button" class="btn-close" data-bs-dismiss="modal"></button>
                </div>
                <div class="modal-body">
                    <form id="changePasswordForm">
                        <div class="mb-3">
                            <label for="currentPassword" class="form-label">Current Password</label>
                            <input type="password" class="form-control" id="currentPassword" required>
                        </div>
                        <div class="mb-3">
                            <label for="newPassword" class="form-label">New Password</label>
                            <input type="password" class="form-control" id="newPassword" required>
                        </div>
                        <div class="mb-3">
                            <label for="confirmPassword" class="form-label">Confirm New Password</label>
                            <input type="password" class="form-control" id="confirmPassword" required>
                        </div>
                        <button type="submit" class="btn btn-primary">Change Password</button>
                    </form>
                </div>
            </div>
        </div>
    </div>

    <div class="modal fade" id="userManagementModal" tabindex="-1">
        <div class="modal-dialog modal-lg">
            <div class="modal-content">
                <div class="modal-header">
                    <h5 class="modal-title">User Management</h5>
                    <button type="button" class="btn-close" data-bs-dismiss="modal"></button>
                </div>
                <div class="modal-body">
                    <div class="mb-3">
                        <button class="btn btn-primary" id="addUserBtn">
                            <i class="fas fa-plus"></i> Add New User
                        </button>
                    </div>
                    <div class="table-responsive">
                        <table class="table table-hover">
                            <thead>
                                <tr>
                                    <th>Username</th>
                                    <th>Role</th>
                                    <th>Created Date</th>
                                    <th>Actions</th>
                                </tr>
                            </thead>
                            <tbody id="userTableBody">
                                <!-- Users will be populated here -->
                            </tbody>
                        </table>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <div class="modal fade" id="addUserModal" tabindex="-1">
        <div class="modal-dialog">
            <div class="modal-content">
                <div class="modal-header">
                    <h5 class="modal-title">Add New User</h5>
                    <button type="button" class="btn-close" data-bs-dismiss="modal"></button>
                </div>
                <div class="modal-body">
                    <form id="addUserForm">
                        <div class="mb-3">
                            <label for="newUsername" class="form-label">Username</label>
                            <input type="text" class="form-control" id="newUsername" required>
                        </div>
                        <div class="mb-3">
                            <label for="newUserPassword" class="form-label">Password</label>
                            <input type="password" class="form-control" id="newUserPassword" required>
                        </div>
                        <div class="mb-3">
                            <label for="newUserRole" class="form-label">Role</label>
                            <select class="form-select" id="newUserRole" required>
                                <option value="user">User</option>
                                <option value="admin">Admin</option>
                            </select>
                        </div>
                        <button type="submit" class="btn btn-primary">Add User</button>
                    </form>
                </div>
            </div>
        </div>
    </div>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.bundle.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
    <script>
        // Data storage
        let vehicles = JSON.parse(localStorage.getItem('vehicles')) || [];
        let customers = JSON.parse(localStorage.getItem('customers')) || [];
        let rentals = JSON.parse(localStorage.getItem('rentals')) || [];
        let payments = JSON.parse(localStorage.getItem('payments')) || [];
        let finesTaxes = JSON.parse(localStorage.getItem('finesTaxes')) || [];
        let returns = JSON.parse(localStorage.getItem('returns')) || [];
        let users = JSON.parse(localStorage.getItem('users')) || [
            { username: 'admin', password: '000000', role: 'admin', created: new Date().toISOString() }
        ];
        let systemSettings = JSON.parse(localStorage.getItem('systemSettings')) || {
            systemName: 'Car Rental System',
            systemLogo: '',
            systemMessage: '',
            backupFrequency: 'daily'
        };
        let currentUser = null;

        // Initialize the application
        document.addEventListener('DOMContentLoaded', function() {
            // Check if user is logged in
            checkLoginStatus();
            
            // Login form handler
            document.getElementById('loginForm').addEventListener('submit', handleLogin);
            
            // Logout handler
            document.getElementById('logoutBtn').addEventListener('click', handleLogout);
            
            // User management
            document.getElementById('addUserBtn').addEventListener('click', function() {
                if (currentUser && currentUser.role === 'admin') {
                    new bootstrap.Modal(document.getElementById('addUserModal')).show();
                }
            });
            
            document.getElementById('addUserForm').addEventListener('submit', addNewUser);
            document.getElementById('changePasswordForm').addEventListener('submit', changePassword);
            
            // System logo upload
            document.getElementById('systemLogo').addEventListener('change', handleLogoUpload);
        });

        // Handle logo upload
        function handleLogoUpload(e) {
            const file = e.target.files[0];
            if (file) {
                const reader = new FileReader();
                reader.onload = function(event) {
                    systemSettings.systemLogo = event.target.result;
                    localStorage.setItem('systemSettings', JSON.stringify(systemSettings));
                    alert('Logo uploaded successfully!');
                };
                reader.readAsDataURL(file);
            }
        }

        // Check login status
        function checkLoginStatus() {
            const savedUser = localStorage.getItem('currentUser');
            if (savedUser) {
                currentUser = JSON.parse(savedUser);
                showMainApp();
            }
        }

        // Handle login
        function handleLogin(e) {
            e.preventDefault();
            
            const username = document.getElementById('username').value;
            const password = document.getElementById('password').value;
            
            // Initialize users first
            initializeUsers();
            
            // Get users from localStorage
            const users = JSON.parse(localStorage.getItem('users')) || [];
            
            // Find user
            const user = users.find(u => u.username === username && u.password === password);
            
            if (user) {
                // Save current user
                currentUser = user;
                localStorage.setItem('currentUser', JSON.stringify(user));
                showMainApp();
            } else {
                alert('Invalid username or password! Please try again.');
                // Clear password field
                document.getElementById('password').value = '';
            }
        }

        // Handle logout
        function handleLogout() {
            currentUser = null;
            localStorage.removeItem('currentUser');
            showLoginScreen();
        }

        // Show login screen
        function showLoginScreen() {
            document.getElementById('loginScreen').style.display = 'flex';
            document.getElementById('mainApp').style.display = 'none';
            document.getElementById('loginForm').reset();
        }

        // Show main application
        function showMainApp() {
            document.getElementById('loginScreen').style.display = 'none';
            document.getElementById('mainApp').style.display = 'block';
            document.getElementById('currentUser').textContent = currentUser.username;
            
            // Update system name
            document.getElementById('systemName').value = systemSettings.systemName;
            document.getElementById('systemMessage').value = systemSettings.systemMessage;
            document.getElementById('backupFrequency').value = systemSettings.backupFrequency;
            
            // Handle user permissions
            handleUserPermissions();
            
            // Initialize application components
            initializeApp();
        }

        // Handle user permissions
        function handleUserPermissions() {
            const adminElements = document.querySelectorAll('.admin-only');
            
            if (currentUser.role === 'admin') {
                // Show all elements for admin
                adminElements.forEach(el => {
                    el.style.display = 'block';
                });
            } else {
                // Hide admin-only elements for regular users
                adminElements.forEach(el => {
                    el.style.display = 'none';
                });
            }
        }

        // Initialize users data
        function initializeUsers() {
            // Save to localStorage if not exists
            if (!localStorage.getItem('users')) {
                localStorage.setItem('users', JSON.stringify(users));
            }
        }

        // Initialize application components
        function initializeApp() {
            // Initialize Chart.js for dashboard
            initializeDashboardChart();
            
            // Load initial data
            loadDashboardData();
            loadVehicleData();
            loadCustomerData();
            loadRentalData();
            loadPaymentData();
            loadFineTaxData();
            loadReturnData();
            loadVehicleHistory();
            loadUsers();
            
            // Setup event listeners for search inputs
            setupSearchFunctionality();
            
            // Form submission handlers
            document.getElementById('addVehicleForm').addEventListener('submit', addVehicle);
            document.getElementById('addCustomerForm').addEventListener('submit', addCustomer);
            document.getElementById('createRentalForm').addEventListener('submit', createRental);
            document.getElementById('returnVehicleForm').addEventListener('submit', returnVehicle);
            document.getElementById('addPaymentForm').addEventListener('submit', addPayment);
            document.getElementById('addFineTaxForm').addEventListener('submit', addFineTax);
            document.getElementById('generateReportForm').addEventListener('submit', generateReport);
            document.getElementById('systemSettingsForm').addEventListener('submit', saveSystemSettings);
            
            // Button event listeners
            document.getElementById('backupBtn').addEventListener('click', backupData);
            document.getElementById('restoreBtn').addEventListener('click', restoreData);
            document.getElementById('exportReportBtn').addEventListener('click', exportReportToCSV);
            document.getElementById('printReportBtn').addEventListener('click', printReport);
            
            // Search button event listeners
            document.getElementById('vehicleSearchBtn').addEventListener('click', searchVehicles);
            document.getElementById('customerSearchBtn').addEventListener('click', searchCustomers);
            document.getElementById('rentalSearchBtn').addEventListener('click', searchRentals);
        }

        // Load users
        function loadUsers() {
            if (currentUser.role !== 'admin') return;
            
            const tableBody = document.getElementById('userTableBody');
            tableBody.innerHTML = '';
            
            users.forEach(user => {
                const row = document.createElement('tr');
                row.innerHTML = `
                    <td>${user.username}</td>
                    <td><span class="badge ${user.role === 'admin' ? 'bg-danger' : 'bg-primary'}">${user.role}</span></td>
                    <td>${new Date(user.created).toLocaleDateString()}</td>
                    <td>
                        ${user.username !== 'admin' ? `
                            <button class="btn btn-sm btn-danger" onclick="deleteUser('${user.username}')">
                                <i class="fas fa-trash"></i>
                            </button>
                        ` : ''}
                    </td>
                `;
                tableBody.appendChild(row);
            });
        }

        // Add new user
        function addNewUser(e) {
            e.preventDefault();
            
            if (currentUser.role !== 'admin') {
                alert('Only admin can add users!');
                return;
            }
            
            const username = document.getElementById('newUsername').value;
            const password = document.getElementById('newUserPassword').value;
            const role = document.getElementById('newUserRole').value;
            
            if (users.find(u => u.username === username)) {
                alert('Username already exists!');
                return;
            }
            
            const newUser = {
                username: username,
                password: password,
                role: role,
                created: new Date().toISOString()
            };
            
            users.push(newUser);
            saveUsers();
            loadUsers();
            
            document.getElementById('addUserForm').reset();
            bootstrap.Modal.getInstance(document.getElementById('addUserModal')).hide();
            
            alert('User added successfully!');
        }

        // Delete user
        function deleteUser(username) {
            if (currentUser.role !== 'admin') {
                alert('Only admin can delete users!');
                return;
            }
            
            if (username === 'admin') {
                alert('Cannot delete admin user!');
                return;
            }
            
            if (confirm(`Are you sure you want to delete user ${username}?`)) {
                users = users.filter(u => u.username !== username);
                saveUsers();
                loadUsers();
                alert('User deleted successfully!');
            }
        }

        // Change password
        function changePassword(e) {
            e.preventDefault();
            
            const currentPassword = document.getElementById('currentPassword').value;
            const newPassword = document.getElementById('newPassword').value;
            const confirmPassword = document.getElementById('confirmPassword').value;
            
            if (currentUser.password !== currentPassword) {
                alert('Current password is incorrect!');
                return;
            }
            
            if (newPassword !== confirmPassword) {
                alert('New passwords do not match!');
                return;
            }
            
            currentUser.password = newPassword;
            const userIndex = users.findIndex(u => u.username === currentUser.username);
            if (userIndex !== -1) {
                users[userIndex].password = newPassword;
            }
            
            saveUsers();
            localStorage.setItem('currentUser', JSON.stringify(currentUser));
            
            document.getElementById('changePasswordForm').reset();
            bootstrap.Modal.getInstance(document.getElementById('changePasswordModal')).hide();
            
            alert('Password changed successfully!');
        }

        // Save users to localStorage
        function saveUsers() {
            localStorage.setItem('users', JSON.stringify(users));
        }

        // Calculate customer debt including fines from vehicle returns
        function calculateCustomerDebt(customerId) {
            // Calculate from rentals
            const customerRentals = rentals.filter(r => r.customerId === customerId);
            const totalRentals = customerRentals.reduce((sum, rental) => sum + rental.total, 0);
            
            // Calculate from vehicle returns (fines)
            const customerReturns = returns.filter(r => {
                const rental = rentals.find(rent => rent.invoiceCode === r.invoiceCode);
                return rental && rental.customerId === customerId;
            });
            const totalFines = customerReturns.reduce((sum, returnItem) => sum + (returnItem.fine || 0), 0);
            
            // Calculate payments
            const customerPayments = payments.filter(p => p.customerId === customerId);
            const totalPaid = customerPayments.reduce((sum, payment) => sum + payment.amount, 0);
            
            // Total debt = rentals + fines - payments
            const currentDebt = totalRentals + totalFines - totalPaid;
            
            return {
                totalRentals,
                totalFines,
                totalPaid,
                currentDebt
            };
        }

        // Initialize dashboard chart
        function initializeDashboardChart() {
            const ctx = document.getElementById('vehicleStatusChart').getContext('2d');
            return new Chart(ctx, {
                type: 'doughnut',
                data: {
                    labels: ['Available', 'Rented', 'Maintenance'],
                    datasets: [{
                        data: [0, 0, 0],
                        backgroundColor: [
                            '#27ae60',
                            '#f39c12',
                            '#e74c3c'
                        ],
                        borderWidth: 1
                    }]
                },
                options: {
                    responsive: true,
                    plugins: {
                        legend: {
                            position: 'bottom',
                        }
                    }
                }
            });
        }

        // Load dashboard data
        function loadDashboardData() {
            // Calculate statistics
            const totalPayments = payments.reduce((sum, payment) => sum + payment.amount, 0);
            const totalFinesTaxes = finesTaxes.reduce((sum, item) => sum + item.amount, 0);
            const availableVehicles = vehicles.filter(v => v.status === 'available').length;
            const rentedVehicles = vehicles.filter(v => v.status === 'rented').length;
            const totalCustomers = customers.length;
            const totalVehicles = vehicles.length;
            
            // Update dashboard cards
            document.getElementById('dashboardStats').innerHTML = `
                <div class="col-xl-3 col-md-6 mb-4">
                    <div class="card dashboard-card border-left-primary shadow h-100 py-2">
                        <div class="card-body">
                            <div class="row no-gutters align-items-center">
                                <div class="col mr-2">
                                    <div class="text-xs font-weight-bold text-primary text-uppercase mb-1">
                                        Total Payments</div>
                                    <div class="h5 mb-0 font-weight-bold text-gray-800">$${totalPayments.toLocaleString()}</div>
                                </div>
                                <div class="col-auto">
                                    <i class="fas fa-dollar-sign fa-2x text-gray-300"></i>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col-xl-3 col-md-6 mb-4">
                    <div class="card dashboard-card border-left-success shadow h-100 py-2">
                        <div class="card-body">
                            <div class="row no-gutters align-items-center">
                                <div class="col mr-2">
                                    <div class="text-xs font-weight-bold text-success text-uppercase mb-1">
                                        Fines & Taxes</div>
                                    <div class="h5 mb-0 font-weight-bold text-gray-800">$${totalFinesTaxes.toLocaleString()}</div>
                                </div>
                                <div class="col-auto">
                                    <i class="fas fa-gavel fa-2x text-gray-300"></i>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col-xl-3 col-md-6 mb-4">
                    <div class="card dashboard-card border-left-info shadow h-100 py-2">
                        <div class="card-body">
                            <div class="row no-gutters align-items-center">
                                <div class="col mr-2">
                                    <div class="text-xs font-weight-bold text-info text-uppercase mb-1">
                                        Available Vehicles</div>
                                    <div class="h5 mb-0 font-weight-bold text-gray-800">${availableVehicles}</div>
                                </div>
                                <div class="col-auto">
                                    <i class="fas fa-car fa-2x text-gray-300"></i>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col-xl-3 col-md-6 mb-4">
                    <div class="card dashboard-card border-left-warning shadow h-100 py-2">
                        <div class="card-body">
                            <div class="row no-gutters align-items-center">
                                <div class="col mr-2">
                                    <div class="text-xs font-weight-bold text-warning text-uppercase mb-1">
                                        Rented Vehicles</div>
                                    <div class="h5 mb-0 font-weight-bold text-gray-800">${rentedVehicles}</div>
                                </div>
                                <div class="col-auto">
                                    <i class="fas fa-car-side fa-2x text-gray-300"></i>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col-xl-3 col-md-6 mb-4">
                    <div class="card dashboard-card border-left-primary shadow h-100 py-2">
                        <div class="card-body">
                            <div class="row no-gutters align-items-center">
                                <div class="col mr-2">
                                    <div class="text-xs font-weight-bold text-primary text-uppercase mb-1">
                                        Total Customers</div>
                                    <div class="h5 mb-0 font-weight-bold text-gray-800">${totalCustomers}</div>
                                </div>
                                <div class="col-auto">
                                    <i class="fas fa-users fa-2x text-gray-300"></i>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col-xl-3 col-md-6 mb-4">
                    <div class="card dashboard-card border-left-success shadow h-100 py-2">
                        <div class="card-body">
                            <div class="row no-gutters align-items-center">
                                <div class="col mr-2">
                                    <div class="text-xs font-weight-bold text-success text-uppercase mb-1">
                                        Total Vehicles</div>
                                    <div class="h5 mb-0 font-weight-bold text-gray-800">${totalVehicles}</div>
                                </div>
                                <div class="col-auto">
                                    <i class="fas fa-car fa-2x text-gray-300"></i>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            `;
            
            // Update chart
            const chart = Chart.getChart('vehicleStatusChart');
            if (chart) {
                chart.data.datasets[0].data = [availableVehicles, rentedVehicles, vehicles.length - availableVehicles - rentedVehicles];
                chart.update();
            }
            
            // Load recent rentals
            loadRecentRentals();
        }

        // Load recent rentals for dashboard
        function loadRecentRentals() {
            const recentRentals = rentals.slice(-5).reverse();
            const tableBody = document.getElementById('recentRentalsTable');
            tableBody.innerHTML = '';
            
            recentRentals.forEach(rental => {
                const customer = customers.find(c => c.id === rental.customerId);
                const vehicle = vehicles.find(v => v.id === rental.vehicleId);
                
                const row = document.createElement('tr');
                row.innerHTML = `
                    <td>${customer ? customer.fullName : 'Unknown'}</td>
                    <td>${vehicle ? vehicle.name : 'Unknown'}</td>
                    <td>${rental.date}</td>
                    <td>$${rental.total}</td>
                    <td><span class="badge ${rental.status === 'returned' ? 'bg-success' : 'bg-warning'}">${rental.status}</span></td>
                `;
                tableBody.appendChild(row);
            });
        }

        // Save all data to localStorage
        function saveAllData() {
            localStorage.setItem('vehicles', JSON.stringify(vehicles));
            localStorage.setItem('customers', JSON.stringify(customers));
            localStorage.setItem('rentals', JSON.stringify(rentals));
            localStorage.setItem('payments', JSON.stringify(payments));
            localStorage.setItem('finesTaxes', JSON.stringify(finesTaxes));
            localStorage.setItem('returns', JSON.stringify(returns));
            localStorage.setItem('systemSettings', JSON.stringify(systemSettings));
            
            // Update dashboard after saving data
            loadDashboardData();
        }

        // Load vehicle data into the table
        function loadVehicleData() {
            const tableBody = document.getElementById('vehicleTableBody');
            tableBody.innerHTML = '';
            
            vehicles.forEach(vehicle => {
                const row = document.createElement('tr');
                row.innerHTML = `
                    <td>${vehicle.name}</td>
                    <td>${vehicle.model}</td>
                    <td>${vehicle.color}</td>
                    <td>${vehicle.plate}</td>
                    <td>${vehicle.odometer.toLocaleString()}</td>
                    <td><span class="badge ${vehicle.status === 'available' ? 'bg-success' : vehicle.status === 'rented' ? 'bg-warning' : 'bg-danger'}">${vehicle.status}</span></td>
                    <td>
                        <button class="btn btn-sm btn-primary" onclick="editVehicle(${vehicle.id})"><i class="fas fa-edit"></i></button>
                        <button class="btn btn-sm btn-danger" onclick="deleteVehicle(${vehicle.id})"><i class="fas fa-trash"></i></button>
                    </td>
                `;
                tableBody.appendChild(row);
            });
        }

        // Load vehicle history
        function loadVehicleHistory() {
            const tableBody = document.getElementById('vehicleHistoryTableBody');
            tableBody.innerHTML = '';
            
            rentals.forEach(rental => {
                const customer = customers.find(c => c.id === rental.customerId);
                const vehicle = vehicles.find(v => v.id === rental.vehicleId);
                const returnInfo = returns.find(r => r.invoiceCode === rental.invoiceCode);
                
                const row = document.createElement('tr');
                row.innerHTML = `
                    <td>${vehicle ? vehicle.name : 'Unknown'}</td>
                    <td>${customer ? customer.fullName : 'Unknown'}</td>
                    <td>${rental.date}</td>
                    <td>${returnInfo ? returnInfo.returnDate : 'Not Returned'}</td>
                    <td>$${rental.total}</td>
                    <td><span class="badge ${rental.status === 'returned' ? 'bg-success' : 'bg-warning'}">${rental.status}</span></td>
                `;
                tableBody.appendChild(row);
            });
        }

        // Load customer data into the table
        function loadCustomerData() {
            const tableBody = document.getElementById('customerTableBody');
            tableBody.innerHTML = '';
            
            customers.forEach(customer => {
                // Calculate total debt for customer including fines from returns
                const debtInfo = calculateCustomerDebt(customer.id);
                
                const row = document.createElement('tr');
                row.innerHTML = `
                    <td>${customer.fullName}</td>
                    <td>${customer.age}</td>
                    <td>${customer.idNumber}</td>
                    <td>${customer.nationality}</td>
                    <td>${customer.contact}</td>
                    <td>$${debtInfo.currentDebt.toLocaleString()}</td>
                    <td>
                        <button class="btn btn-sm btn-primary" onclick="editCustomer(${customer.id})"><i class="fas fa-edit"></i></button>
                        <button class="btn btn-sm btn-danger" onclick="deleteCustomer(${customer.id})"><i class="fas fa-trash"></i></button>
                    </td>
                `;
                tableBody.appendChild(row);
            });
        }

        // Load rental data into the table
        function loadRentalData() {
            const tableBody = document.getElementById('rentalTableBody');
            tableBody.innerHTML = '';
            
            rentals.forEach(rental => {
                const customer = customers.find(c => c.id === rental.customerId);
                const vehicle = vehicles.find(v => v.id === rental.vehicleId);
                
                const row = document.createElement('tr');
                row.innerHTML = `
                    <td>${rental.invoiceCode}</td>
                    <td>${customer ? customer.fullName : 'Unknown'}</td>
                    <td>${vehicle ? vehicle.name : 'Unknown'}</td>
                    <td>${rental.date}</td>
                    <td>$${rental.total}</td>
                    <td><span class="badge ${rental.status === 'returned' ? 'bg-success' : 'bg-warning'}">${rental.status}</span></td>
                    <td>
                        <button class="btn btn-sm btn-primary" onclick="editRental(${rental.id})"><i class="fas fa-edit"></i></button>
                        <button class="btn btn-sm btn-danger" onclick="deleteRental(${rental.id})"><i class="fas fa-trash"></i></button>
                    </td>
                `;
                tableBody.appendChild(row);
            });
        }

        // Load payment data into the table
        function loadPaymentData() {
            const tableBody = document.getElementById('paymentTableBody');
            tableBody.innerHTML = '';
            
            payments.forEach(payment => {
                const customer = customers.find(c => c.id === payment.customerId);
                
                const row = document.createElement('tr');
                row.innerHTML = `
                    <td>${payment.date}</td>
                    <td>${customer ? customer.fullName : 'Unknown'}</td>
                    <td>$${payment.amount}</td>
                    <td>
                        <button class="btn btn-sm btn-primary" onclick="editPayment(${payment.id})"><i class="fas fa-edit"></i></button>
                        <button class="btn btn-sm btn-danger" onclick="deletePayment(${payment.id})"><i class="fas fa-trash"></i></button>
                    </td>
                `;
                tableBody.appendChild(row);
            });
        }

        // Load fine/tax data into the table
        function loadFineTaxData() {
            const tableBody = document.getElementById('fineTaxTableBody');
            tableBody.innerHTML = '';
            
            finesTaxes.forEach(fineTax => {
                const row = document.createElement('tr');
                row.innerHTML = `
                    <td>${fineTax.date}</td>
                    <td><span class="badge ${fineTax.type === 'fine' ? 'bg-danger' : 'bg-warning'}">${fineTax.type}</span></td>
                    <td>$${fineTax.amount}</td>
                    <td>${fineTax.invoiceCode}</td>
                    <td>
                        <button class="btn btn-sm btn-primary" onclick="editFineTax(${fineTax.id})"><i class="fas fa-edit"></i></button>
                        <button class="btn btn-sm btn-danger" onclick="deleteFineTax(${fineTax.id})"><i class="fas fa-trash"></i></button>
                    </td>
                `;
                tableBody.appendChild(row);
            });
        }

        // Load return data into the table
        function loadReturnData() {
            const tableBody = document.getElementById('returnTableBody');
            tableBody.innerHTML = '';
            
            returns.forEach(returnItem => {
                const rental = rentals.find(r => r.invoiceCode === returnItem.invoiceCode);
                const customer = rental ? customers.find(c => c.id === rental.customerId) : null;
                const vehicle = rental ? vehicles.find(v => v.id === rental.vehicleId) : null;
                
                const row = document.createElement('tr');
                row.innerHTML = `
                    <td>${returnItem.invoiceCode}</td>
                    <td>${customer ? customer.fullName : 'Unknown'}</td>
                    <td>${vehicle ? vehicle.name : 'Unknown'}</td>
                    <td>${returnItem.returnDate}</td>
                    <td>$${returnItem.fine || 0}</td>
                    <td>$${(returnItem.fine || 0)}</td>
                `;
                tableBody.appendChild(row);
            });
        }

        // Add a new vehicle
        function addVehicle(e) {
            e.preventDefault();
            
            const newVehicle = {
                id: vehicles.length > 0 ? Math.max(...vehicles.map(v => v.id)) + 1 : 1,
                name: document.getElementById('vehicleName').value,
                model: document.getElementById('vehicleModel').value,
                color: document.getElementById('vehicleColor').value,
                plate: document.getElementById('vehiclePlate').value,
                vin: document.getElementById('vehicleVin').value,
                odometer: parseInt(document.getElementById('vehicleOdometer').value),
                status: 'available'
            };
            
            vehicles.push(newVehicle);
            saveAllData();
            loadVehicleData();
            loadVehicleHistory();
            
            // Reset form
            document.getElementById('addVehicleForm').reset();
            
            alert('Vehicle added successfully!');
        }

        // Add a new customer
        function addCustomer(e) {
            e.preventDefault();
            
            const newCustomer = {
                id: customers.length > 0 ? Math.max(...customers.map(c => c.id)) + 1 : 1,
                fullName: document.getElementById('customerFullName').value,
                age: parseInt(document.getElementById('customerAge').value),
                idNumber: document.getElementById('customerId').value,
                nationality: document.getElementById('customerNationality').value,
                contact: document.getElementById('customerContact').value,
                address: document.getElementById('customerAddress').value
            };
            
            customers.push(newCustomer);
            saveAllData();
            loadCustomerData();
            
            // Reset form
            document.getElementById('addCustomerForm').reset();
            
            alert('Customer added successfully!');
        }

        // Create a new rental
        function createRental(e) {
            e.preventDefault();
            
            const customerName = document.getElementById('rentalCustomer').value;
            const vehicleName = document.getElementById('rentalVehicle').value;
            
            const customer = customers.find(c => c.fullName === customerName);
            const vehicle = vehicles.find(v => v.name === vehicleName);
            
            if (!customer) {
                alert('Customer not found!');
                return;
            }
            
            if (!vehicle) {
                alert('Vehicle not found!');
                return;
            }
            
            if (vehicle.status !== 'available') {
                alert('Vehicle is not available for rental!');
                return;
            }
            
            const rentalAmount = parseFloat(document.getElementById('rentalAmount').value);
            const rentalDays = parseInt(document.getElementById('rentalDays').value);
            const invoiceCode = document.getElementById('invoiceCode').value || `INV${Date.now()}`;
            
            const newRental = {
                id: rentals.length > 0 ? Math.max(...rentals.map(r => r.id)) + 1 : 1,
                invoiceCode: invoiceCode,
                customerId: customer.id,
                vehicleId: vehicle.id,
                date: new Date().toISOString().split('T')[0],
                amount: rentalAmount,
                days: rentalDays,
                total: rentalAmount,
                status: 'active'
            };
            
            rentals.push(newRental);
            
            // Update vehicle status
            vehicle.status = 'rented';
            
            saveAllData();
            loadRentalData();
            loadVehicleData();
            loadVehicleHistory();
            
            // Reset form
            document.getElementById('createRentalForm').reset();
            
            alert('Rental created successfully!');
        }

        // Return a vehicle
        function returnVehicle(e) {
            e.preventDefault();
            
            const invoiceCode = document.getElementById('returnInvoice').value;
            const fineAmount = parseFloat(document.getElementById('fineAmount').value) || 0;
            
            const rental = rentals.find(r => r.invoiceCode === invoiceCode);
            
            if (!rental) {
                alert('Rental not found with this invoice code!');
                return;
            }
            
            if (rental.status === 'returned') {
                alert('This vehicle has already been returned!');
                return;
            }
            
            // Update rental status
            rental.status = 'returned';
            
            // Update vehicle status
            const vehicle = vehicles.find(v => v.id === rental.vehicleId);
            if (vehicle) {
                vehicle.status = 'available';
            }
            
            // Add to returns history
            const newReturn = {
                id: returns.length > 0 ? Math.max(...returns.map(r => r.id)) + 1 : 1,
                invoiceCode: invoiceCode,
                returnDate: new Date().toISOString().split('T')[0],
                fine: fineAmount
            };
            
            returns.push(newReturn);
            
            // Add fines if any
            if (fineAmount > 0) {
                const newFine = {
                    id: finesTaxes.length > 0 ? Math.max(...finesTaxes.map(f => f.id)) + 1 : 1,
                    type: 'fine',
                    amount: fineAmount,
                    invoiceCode: invoiceCode,
                    date: new Date().toISOString().split('T')[0]
                };
                finesTaxes.push(newFine);
            }
            
            saveAllData();
            loadRentalData();
            loadVehicleData();
            loadReturnData();
            loadFineTaxData();
            loadVehicleHistory();
            loadCustomerData();
            
            // Reset form
            document.getElementById('returnVehicleForm').reset();
            
            alert('Vehicle returned successfully!');
        }

        // Add a new payment
        function addPayment(e) {
            e.preventDefault();
            
            const customerName = document.getElementById('debtCustomer').value;
            const customer = customers.find(c => c.fullName === customerName);
            
            if (!customer) {
                alert('Customer not found!');
                return;
            }
            
            const paymentAmount = parseFloat(document.getElementById('paymentAmount').value);
            const paymentDate = document.getElementById('paymentDate').value || new Date().toISOString().split('T')[0];
            
            const newPayment = {
                id: payments.length > 0 ? Math.max(...payments.map(p => p.id)) + 1 : 1,
                customerId: customer.id,
                amount: paymentAmount,
                date: paymentDate
            };
            
            payments.push(newPayment);
            saveAllData();
            loadPaymentData();
            loadCustomerData();
            
            // Reset form
            document.getElementById('addPaymentForm').reset();
            
            alert('Payment added successfully!');
        }

        // Add a new fine/tax
        function addFineTax(e) {
            e.preventDefault();
            
            const type = document.getElementById('fineTaxType').value;
            const amount = parseFloat(document.getElementById('fineTaxAmount').value);
            const invoiceCode = document.getElementById('fineTaxInvoice').value;
            
            const newFineTax = {
                id: finesTaxes.length > 0 ? Math.max(...finesTaxes.map(f => f.id)) + 1 : 1,
                type: type,
                amount: amount,
                invoiceCode: invoiceCode,
                date: new Date().toISOString().split('T')[0]
            };
            
            finesTaxes.push(newFineTax);
            saveAllData();
            loadFineTaxData();
            
            // Reset form
            document.getElementById('addFineTaxForm').reset();
            
            alert(`${type === 'fine' ? 'Fine' : 'Tax'} added successfully!`);
        }

        // Generate report
        function generateReport(e) {
            e.preventDefault();
            
            const startDate = document.getElementById('reportStartDate').value;
            const endDate = document.getElementById('reportEndDate').value;
            const reportType = document.getElementById('reportType').value;
            const vehicleFilter = document.getElementById('reportVehicle').value;
            const format = document.getElementById('reportFormat').value;
            
            if (!startDate || !endDate) {
                alert('Please select both start and end dates.');
                return;
            }
            
            let data = [];
            let headers = [];
            let title = '';
            
            switch (reportType) {
                case 'rentals':
                    data = rentals.filter(rental => rental.date >= startDate && rental.date <= endDate);
                    if (vehicleFilter) {
                        data = data.filter(rental => {
                            const vehicle = vehicles.find(v => v.id === rental.vehicleId);
                            return vehicle && (
                                vehicle.name.toLowerCase().includes(vehicleFilter.toLowerCase()) ||
                                vehicle.plate.toLowerCase().includes(vehicleFilter.toLowerCase())
                            );
                        });
                    }
                    headers = ['Invoice Code', 'Customer', 'Vehicle', 'Date', 'Amount', 'Status'];
                    title = 'Rentals Report';
                    break;
                    
                case 'payments':
                    data = payments.filter(payment => payment.date >= startDate && payment.date <= endDate);
                    headers = ['Date', 'Customer', 'Amount'];
                    title = 'Payments Report';
                    break;
                    
                case 'fines':
                    data = finesTaxes.filter(item => item.date >= startDate && item.date <= endDate);
                    headers = ['Date', 'Type', 'Amount', 'Invoice Code'];
                    title = 'Fines & Taxes Report';
                    break;
                    
                case 'returns':
                    data = returns.filter(returnItem => returnItem.returnDate >= startDate && returnItem.returnDate <= endDate);
                    headers = ['Invoice Code', 'Return Date', 'Fine', 'Total'];
                    title = 'Vehicle Returns Report';
                    break;
            }
            
            // Display results
            displayReportResults(data, headers, title);
            
            // If format is print, print the report
            if (format === 'print') {
                printReport();
            }
        }

        // Display report results
        function displayReportResults(data, headers, title) {
            const resultsHead = document.getElementById('reportResultsHead');
            const resultsBody = document.getElementById('reportResultsBody');
            const reportTitle = document.getElementById('reportTitle');
            
            // Set title
            reportTitle.textContent = title;
            
            // Create headers
            resultsHead.innerHTML = '';
            const headerRow = document.createElement('tr');
            headers.forEach(header => {
                const th = document.createElement('th');
                th.textContent = header;
                headerRow.appendChild(th);
            });
            resultsHead.appendChild(headerRow);
            
            // Create data rows
            resultsBody.innerHTML = '';
            data.forEach(item => {
                const row = document.createElement('tr');
                
                // Based on report type, create appropriate cells
                if (title === 'Rentals Report') {
                    const customer = customers.find(c => c.id === item.customerId);
                    const vehicle = vehicles.find(v => v.id === item.vehicleId);
                    
                    row.innerHTML = `
                        <td>${item.invoiceCode}</td>
                        <td>${customer ? customer.fullName : 'Unknown'}</td>
                        <td>${vehicle ? vehicle.name : 'Unknown'}</td>
                        <td>${item.date}</td>
                        <td>$${item.total}</td>
                        <td>${item.status}</td>
                    `;
                } else if (title === 'Payments Report') {
                    const customer = customers.find(c => c.id === item.customerId);
                    
                    row.innerHTML = `
                        <td>${item.date}</td>
                        <td>${customer ? customer.fullName : 'Unknown'}</td>
                        <td>$${item.amount}</td>
                    `;
                } else if (title === 'Fines & Taxes Report') {
                    row.innerHTML = `
                        <td>${item.date}</td>
                        <td>${item.type}</td>
                        <td>$${item.amount}</td>
                        <td>${item.invoiceCode}</td>
                    `;
                } else if (title === 'Vehicle Returns Report') {
                    row.innerHTML = `
                        <td>${item.invoiceCode}</td>
                        <td>${item.returnDate}</td>
                        <td>$${item.fine || 0}</td>
                        <td>$${(item.fine || 0)}</td>
                    `;
                }
                
                resultsBody.appendChild(row);
            });
            
            // Show results card
            document.getElementById('reportResultsCard').style.display = 'block';
        }

        // Save system settings
        function saveSystemSettings(e) {
            e.preventDefault();
            
            const systemName = document.getElementById('systemName').value;
            const systemMessage = document.getElementById('systemMessage').value;
            const backupFrequency = document.getElementById('backupFrequency').value;
            
            systemSettings.systemName = systemName;
            systemSettings.systemMessage = systemMessage;
            systemSettings.backupFrequency = backupFrequency;
            
            localStorage.setItem('systemSettings', JSON.stringify(systemSettings));
            
            alert('System settings saved successfully!');
        }

        // Backup data
        function backupData() {
            const data = {
                vehicles: vehicles,
                customers: customers,
                rentals: rentals,
                payments: payments,
                finesTaxes: finesTaxes,
                returns: returns,
                users: users,
                systemSettings: systemSettings,
                backupDate: new Date().toISOString()
            };
            
            const dataStr = JSON.stringify(data, null, 2);
            const dataBlob = new Blob([dataStr], {type: 'application/json'});
            
            const url = URL.createObjectURL(dataBlob);
            const a = document.createElement('a');
            a.href = url;
            a.download = `car-rental-backup-${new Date().toISOString().split('T')[0]}.json`;
            document.body.appendChild(a);
            a.click();
            document.body.removeChild(a);
            URL.revokeObjectURL(url);
            
            alert('Backup created successfully!');
        }

        // Restore data
        function restoreData() {
            const input = document.createElement('input');
            input.type = 'file';
            input.accept = '.json';
            
            input.onchange = e => {
                const file = e.target.files[0];
                const reader = new FileReader();
                
                reader.onload = function(event) {
                    try {
                        const data = JSON.parse(event.target.result);
                        
                        if (data.vehicles && data.customers && data.rentals) {
                            vehicles = data.vehicles;
                            customers = data.customers;
                            rentals = data.rentals;
                            payments = data.payments || [];
                            finesTaxes = data.finesTaxes || [];
                            returns = data.returns || [];
                            users = data.users || users;
                            systemSettings = data.systemSettings || systemSettings;
                            
                            saveAllData();
                            saveUsers();
                            loadVehicleData();
                            loadCustomerData();
                            loadRentalData();
                            loadPaymentData();
                            loadFineTaxData();
                            loadReturnData();
                            loadVehicleHistory();
                            loadUsers();
                            
                            // Update system settings in UI
                            document.getElementById('systemName').value = systemSettings.systemName;
                            document.getElementById('systemMessage').value = systemSettings.systemMessage;
                            document.getElementById('backupFrequency').value = systemSettings.backupFrequency;
                            
                            alert('Data restored successfully!');
                        } else {
                            alert('Invalid backup file format.');
                        }
                    } catch (error) {
                        alert('Error reading backup file: ' + error.message);
                    }
                };
                
                reader.readAsText(file);
            };
            
            input.click();
        }

        // Export report to CSV
        function exportReportToCSV() {
            const table = document.getElementById('reportResultsTable');
            let csv = [];
            const rows = table.querySelectorAll('tr');
            
            for (let i = 0; i < rows.length; i++) {
                const row = [], cols = rows[i].querySelectorAll('td, th');
                
                for (let j = 0; j < cols.length; j++) {
                    row.push(cols[j].innerText);
                }
                
                csv.push(row.join(','));
            }
            
            const csvStr = csv.join('\n');
            const blob = new Blob([csvStr], {type: 'text/csv'});
            const url = URL.createObjectURL(blob);
            const a = document.createElement('a');
            a.href = url;
            a.download = `rental-report-${new Date().toISOString().split('T')[0]}.csv`;
            document.body.appendChild(a);
            a.click();
            document.body.removeChild(a);
            URL.revokeObjectURL(url);
        }

        // Print report
        function printReport() {
            const printContent = document.getElementById('reportResultsCard').innerHTML;
            const originalContent = document.body.innerHTML;
            
            document.body.innerHTML = `
                <div class="container">
                    <div class="invoice-logo">
                        ${systemSettings.systemLogo ? `<img src="${systemSettings.systemLogo}" alt="Company Logo" style="max-width: 150px;">` : '<i class="fas fa-car-side fa-3x"></i>'}
                        <h3>${systemSettings.systemName}</h3>
                    </div>
                    <h2 class="text-center my-4" id="printReportTitle">Report</h2>
                    ${printContent}
                </div>
            `;
            
            window.print();
            document.body.innerHTML = originalContent;
        }

        // Setup search functionality with autocomplete
        function setupSearchFunctionality() {
            // Customer search for rentals
            const rentalCustomerInput = document.getElementById('rentalCustomer');
            const customerSuggestions = document.getElementById('customerSuggestions');
            
            rentalCustomerInput.addEventListener('input', function() {
                const searchTerm = this.value.toLowerCase();
                customerSuggestions.innerHTML = '';
                
                if (searchTerm.length > 0) {
                    const filteredCustomers = customers.filter(customer => 
                        customer.fullName.toLowerCase().includes(searchTerm)
                    );
                    
                    if (filteredCustomers.length > 0) {
                        customerSuggestions.style.display = 'block';
                        
                        filteredCustomers.forEach(customer => {
                            const item = document.createElement('div');
                            item.className = 'suggestion-item';
                            item.textContent = customer.fullName;
                            item.addEventListener('click', function() {
                                rentalCustomerInput.value = customer.fullName;
                                customerSuggestions.style.display = 'none';
                            });
                            customerSuggestions.appendChild(item);
                        });
                    } else {
                        customerSuggestions.style.display = 'none';
                    }
                } else {
                    customerSuggestions.style.display = 'none';
                }
            });
            
            // Vehicle search for rentals
            const rentalVehicleInput = document.getElementById('rentalVehicle');
            const vehicleSuggestions = document.getElementById('vehicleSuggestions');
            
            rentalVehicleInput.addEventListener('input', function() {
                const searchTerm = this.value.toLowerCase();
                vehicleSuggestions.innerHTML = '';
                
                if (searchTerm.length > 0) {
                    const filteredVehicles = vehicles.filter(vehicle => 
                        vehicle.name.toLowerCase().includes(searchTerm) && vehicle.status === 'available'
                    );
                    
                    if (filteredVehicles.length > 0) {
                        vehicleSuggestions.style.display = 'block';
                        
                        filteredVehicles.forEach(vehicle => {
                            const item = document.createElement('div');
                            item.className = 'suggestion-item';
                            item.textContent = vehicle.name;
                            item.addEventListener('click', function() {
                                rentalVehicleInput.value = vehicle.name;
                                vehicleSuggestions.style.display = 'none';
                            });
                            vehicleSuggestions.appendChild(item);
                        });
                    } else {
                        vehicleSuggestions.style.display = 'none';
                    }
                } else {
                    vehicleSuggestions.style.display = 'none';
                }
            });
            
            // Customer search for debts
            const debtCustomerInput = document.getElementById('debtCustomer');
            const debtCustomerSuggestions = document.getElementById('debtCustomerSuggestions');
            
            debtCustomerInput.addEventListener('input', function() {
                const searchTerm = this.value.toLowerCase();
                debtCustomerSuggestions.innerHTML = '';
                
                if (searchTerm.length > 0) {
                    const filteredCustomers = customers.filter(customer => 
                        customer.fullName.toLowerCase().includes(searchTerm)
                    );
                    
                    if (filteredCustomers.length > 0) {
                        debtCustomerSuggestions.style.display = 'block';
                        
                        filteredCustomers.forEach(customer => {
                            const item = document.createElement('div');
                            item.className = 'suggestion-item';
                            item.textContent = customer.fullName;
                            item.addEventListener('click', function() {
                                debtCustomerInput.value = customer.fullName;
                                debtCustomerSuggestions.style.display = 'none';
                                
                                // Calculate and display current debt including fines from returns
                                const debtInfo = calculateCustomerDebt(customer.id);
                                
                                document.getElementById('currentDebt').textContent = `$${debtInfo.currentDebt.toLocaleString()}`;
                                
                                // Show customer summary
                                const summary = document.getElementById('customerDebtSummary');
                                summary.innerHTML = `
                                    <p><strong>Total Rentals Amount:</strong> $${debtInfo.totalRentals.toLocaleString()}</p>
                                    <p><strong>Total Fines from Returns:</strong> $${debtInfo.totalFines.toLocaleString()}</p>
                                    <p><strong>Total Paid:</strong> $${debtInfo.totalPaid.toLocaleString()}</p>
                                    <p><strong>Remaining Debt:</strong> $${debtInfo.currentDebt.toLocaleString()}</p>
                                `;
                            });
                            debtCustomerSuggestions.appendChild(item);
                        });
                    } else {
                        debtCustomerSuggestions.style.display = 'none';
                    }
                } else {
                    debtCustomerSuggestions.style.display = 'none';
                }
            });
            
            // Invoice search for returns
            const returnInvoiceInput = document.getElementById('returnInvoice');
            const returnInvoiceSuggestions = document.getElementById('returnInvoiceSuggestions');
            
            returnInvoiceInput.addEventListener('input', function() {
                const searchTerm = this.value.toLowerCase();
                returnInvoiceSuggestions.innerHTML = '';
                
                if (searchTerm.length > 0) {
                    const filteredInvoices = rentals.filter(rental => 
                        rental.invoiceCode.toLowerCase().includes(searchTerm) && rental.status === 'active'
                    );
                    
                    if (filteredInvoices.length > 0) {
                        returnInvoiceSuggestions.style.display = 'block';
                        
                        filteredInvoices.forEach(rental => {
                            const item = document.createElement('div');
                            item.className = 'suggestion-item';
                            item.textContent = rental.invoiceCode;
                            item.addEventListener('click', function() {
                                returnInvoiceInput.value = rental.invoiceCode;
                                returnInvoiceSuggestions.style.display = 'none';
                            });
                            returnInvoiceSuggestions.appendChild(item);
                        });
                    } else {
                        returnInvoiceSuggestions.style.display = 'none';
                    }
                } else {
                    returnInvoiceSuggestions.style.display = 'none';
                }
            });
            
            // Invoice search for fines/taxes
            const fineTaxInvoiceInput = document.getElementById('fineTaxInvoice');
            const invoiceSuggestions = document.getElementById('invoiceSuggestions');
            
            fineTaxInvoiceInput.addEventListener('input', function() {
                const searchTerm = this.value.toLowerCase();
                invoiceSuggestions.innerHTML = '';
                
                if (searchTerm.length > 0) {
                    const filteredInvoices = rentals.filter(rental => 
                        rental.invoiceCode.toLowerCase().includes(searchTerm)
                    );
                    
                    if (filteredInvoices.length > 0) {
                        invoiceSuggestions.style.display = 'block';
                        
                        filteredInvoices.forEach(rental => {
                            const item = document.createElement('div');
                            item.className = 'suggestion-item';
                            item.textContent = rental.invoiceCode;
                            item.addEventListener('click', function() {
                                fineTaxInvoiceInput.value = rental.invoiceCode;
                                invoiceSuggestions.style.display = 'none';
                            });
                            invoiceSuggestions.appendChild(item);
                        });
                    } else {
                        invoiceSuggestions.style.display = 'none';
                    }
                } else {
                    invoiceSuggestions.style.display = 'none';
                }
            });
        }

        // Search vehicles
        function searchVehicles() {
            const searchTerm = document.getElementById('vehicleSearch').value.toLowerCase();
            const tableBody = document.getElementById('vehicleTableBody');
            tableBody.innerHTML = '';
            
            const filteredVehicles = vehicles.filter(vehicle => 
                vehicle.name.toLowerCase().includes(searchTerm) ||
                vehicle.model.toLowerCase().includes(searchTerm) ||
                vehicle.plate.toLowerCase().includes(searchTerm)
            );
            
            filteredVehicles.forEach(vehicle => {
                const row = document.createElement('tr');
                row.innerHTML = `
                    <td>${vehicle.name}</td>
                    <td>${vehicle.model}</td>
                    <td>${vehicle.color}</td>
                    <td>${vehicle.plate}</td>
                    <td>${vehicle.odometer.toLocaleString()}</td>
                    <td><span class="badge ${vehicle.status === 'available' ? 'bg-success' : vehicle.status === 'rented' ? 'bg-warning' : 'bg-danger'}">${vehicle.status}</span></td>
                    <td>
                        <button class="btn btn-sm btn-primary" onclick="editVehicle(${vehicle.id})"><i class="fas fa-edit"></i></button>
                        <button class="btn btn-sm btn-danger" onclick="deleteVehicle(${vehicle.id})"><i class="fas fa-trash"></i></button>
                    </td>
                `;
                tableBody.appendChild(row);
            });
        }

        // Search customers
        function searchCustomers() {
            const searchTerm = document.getElementById('customerSearch').value.toLowerCase();
            const tableBody = document.getElementById('customerTableBody');
            tableBody.innerHTML = '';
            
            const filteredCustomers = customers.filter(customer => 
                customer.fullName.toLowerCase().includes(searchTerm) ||
                customer.idNumber.toLowerCase().includes(searchTerm) ||
                customer.contact.toLowerCase().includes(searchTerm)
            );
            
            filteredCustomers.forEach(customer => {
                // Calculate total debt for customer including fines from returns
                const debtInfo = calculateCustomerDebt(customer.id);
                
                const row = document.createElement('tr');
                row.innerHTML = `
                    <td>${customer.fullName}</td>
                    <td>${customer.age}</td>
                    <td>${customer.idNumber}</td>
                    <td>${customer.nationality}</td>
                    <td>${customer.contact}</td>
                    <td>$${debtInfo.currentDebt.toLocaleString()}</td>
                    <td>
                        <button class="btn btn-sm btn-primary" onclick="editCustomer(${customer.id})"><i class="fas fa-edit"></i></button>
                        <button class="btn btn-sm btn-danger" onclick="deleteCustomer(${customer.id})"><i class="fas fa-trash"></i></button>
                    </td>
                `;
                tableBody.appendChild(row);
            });
        }

        // Search rentals
        function searchRentals() {
            const searchTerm = document.getElementById('rentalSearch').value.toLowerCase();
            const tableBody = document.getElementById('rentalTableBody');
            tableBody.innerHTML = '';
            
            const filteredRentals = rentals.filter(rental => 
                rental.invoiceCode.toLowerCase().includes(searchTerm)
            );
            
            filteredRentals.forEach(rental => {
                const customer = customers.find(c => c.id === rental.customerId);
                const vehicle = vehicles.find(v => v.id === rental.vehicleId);
                
                const row = document.createElement('tr');
                row.innerHTML = `
                    <td>${rental.invoiceCode}</td>
                    <td>${customer ? customer.fullName : 'Unknown'}</td>
                    <td>${vehicle ? vehicle.name : 'Unknown'}</td>
                    <td>${rental.date}</td>
                    <td>$${rental.total}</td>
                    <td><span class="badge ${rental.status === 'returned' ? 'bg-success' : 'bg-warning'}">${rental.status}</span></td>
                    <td>
                        <button class="btn btn-sm btn-primary" onclick="editRental(${rental.id})"><i class="fas fa-edit"></i></button>
                        <button class="btn btn-sm btn-danger" onclick="deleteRental(${rental.id})"><i class="fas fa-trash"></i></button>
                    </td>
                `;
                tableBody.appendChild(row);
            });
        }

        // Placeholder functions for edit/delete operations
        function editVehicle(id) {
            alert(`Edit vehicle with ID: ${id} - This functionality would open an edit form in a real application.`);
        }

        function deleteVehicle(id) {
            if (confirm('Are you sure you want to delete this vehicle?')) {
                vehicles = vehicles.filter(vehicle => vehicle.id !== id);
                saveAllData();
                loadVehicleData();
                loadVehicleHistory();
                alert('Vehicle deleted successfully!');
            }
        }

        function editCustomer(id) {
            alert(`Edit customer with ID: ${id} - This functionality would open an edit form in a real application.`);
        }

        function deleteCustomer(id) {
            if (confirm('Are you sure you want to delete this customer?')) {
                customers = customers.filter(customer => customer.id !== id);
                saveAllData();
                loadCustomerData();
                alert('Customer deleted successfully!');
            }
        }

        function editRental(id) {
            alert(`Edit rental with ID: ${id} - This functionality would open an edit form in a real application.`);
        }

        function deleteRental(id) {
            if (confirm('Are you sure you want to delete this rental?')) {
                const rental = rentals.find(r => r.id === id);
                if (rental) {
                    // Make the vehicle available again
                    const vehicle = vehicles.find(v => v.id === rental.vehicleId);
                    if (vehicle) {
                        vehicle.status = 'available';
                    }
                }
                
                rentals = rentals.filter(rental => rental.id !== id);
                saveAllData();
                loadRentalData();
                loadVehicleData();
                loadVehicleHistory();
                alert('Rental deleted successfully!');
            }
        }

        function editPayment(id) {
            alert(`Edit payment with ID: ${id} - This functionality would open an edit form in a real application.`);
        }

        function deletePayment(id) {
            if (confirm('Are you sure you want to delete this payment?')) {
                payments = payments.filter(payment => payment.id !== id);
                saveAllData();
                loadPaymentData();
                alert('Payment deleted successfully!');
            }
        }

        function editFineTax(id) {
            alert(`Edit fine/tax with ID: ${id} - This functionality would open an edit form in a real application.`);
        }

        function deleteFineTax(id) {
            if (confirm('Are you sure you want to delete this fine/tax?')) {
                finesTaxes = finesTaxes.filter(fineTax => fineTax.id !== id);
                saveAllData();
                loadFineTaxData();
                alert('Fine/Tax deleted successfully!');
            }
        }
    </script>
</body>
</html>
