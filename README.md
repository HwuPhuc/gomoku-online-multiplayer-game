# Hệ thống chơi cờ caro trực tuyến (Gomoku Online Multiplayer Game)

Chú thích: Thông tin được viết bằng tiếng Anh ở phía dưới/ English version below.  
Dự án xây dựng hệ thống chơi cờ caro trực tuyến sử dụng Java theo mô hình Client-Server.  
Người chơi có thể đăng nhập, tạo phòng, tham gia phòng và thi đấu với nhau thông qua mạng. Hệ thống đồng thời cung cấp công cụ quản trị dành cho Admin.  

## Thành Phần Dự Án

### Gomoku Server

Thành phần này dành cho quản trị viên

- Xác thực người dùng  
- Quản lý phòng chơi  
- Điều phối trận đấu  
- Đồng bộ trạng thái trò chơi  
- Quản trị hệ thống  

Repository: [GomokuServer](https://github.com/HwuPhuc/GomokuServer)   

### Gomoku Client

Ứng dụng dành cho người chơi:

- Đăng ký tài khoản
- Đăng nhập
- Tạo và tham gia phòng để chơi với bạn
- Chơi cờ trực tuyến
- Chat trong trận đấu với đối phương
- Kiểm tra thông tin/ thông số cá nhân (Tổng số trận/số trận thắng/số trận thua)

Repository: [GomokuClient](https://github.com/HwuPhuc/GomokuClient)  

## Chức Năng Chính
 
- Chơi cờ caro trực tuyến nhiều người chơi
- Đồng bộ nước đi theo thời gian thực
- Tạo và tham gia phòng chơi
- Quản lý trận đấu
- Quản trị hệ thống

# Gomoku Online Multiplayer Game

A real-time online Gomoku (Five in a Row) game built with Java using a Client-Server architecture.  
The system allows multiple players to connect to a central server to play Gomoku, create game rooms, compete against each other in real time, and be managed by administrators.  

## Repositories

### Server

Game server responsible for:

- User authentication
- Room management
- Match coordination
- Game state synchronization
- Administrator management

Repository: [GomokuServer](https://github.com/HwuPhuc/GomokuServer)  

### Client

Desktop application used by players.

Features:

- Login/Register
- Create/Join Room
- Real-time Gameplay
- Chat while playing
- Check personal statistics (Game played/Win/Lose)

Repository: [GomokuClient](https://github.com/HwuPhuc/GomokuClient)  
## Features

- Multiplayer online gameplay
- Real-time move synchronization
- Multi-threaded server
- User authentication
- Room creation and matchmaking
- Administrator management system
