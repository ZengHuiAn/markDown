
#cocoscreator 
####发送全局事件 
	cc.game.emit("event");
	
####接收
	cc.game.on("event");		
	
###开启物体碰撞
	cc.director.getCollisionManager().enabled = true;   