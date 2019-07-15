實作 todo list功能

建立一資料庫
CREATE TABLE `todolist` (
  `todoId` int(11) NOT NULL AUTO_INCREMENT,
  `content` varchar(255) DEFAULT NULL,
  `status` varchar(20) DEFAULT NULL,
  `datetime` datetime DEFAULT NULL,
  `created_at` datetime DEFAULT NULL,
  `updated_at` datetime DEFAULT NULL,
  PRIMARY KEY (`todoId`)
) ENGINE=InnoDB AUTO_INCREMENT=11 DEFAULT CHARSET=utf8;

content: 待辦事件內容
status: todo-待辦中、doing-辦理中、done-完成
datetime: 待辦事件開始時間

