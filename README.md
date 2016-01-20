# IOLoopTest


////////////////////////////////////

var callbackList = function(){

	this.cblist = [];
}
var cblProto = callbackList.prototype；
cblProto.add = function(...){cblist.push(...)}
cblProto.remove = function(){return cblist.pull();}



var Pub = function(list){this.list = list.cblist;}
var pubProto = Pub.prototype;
pubProto.pub =  function(){
	cb.add();
}



var sub = function(list){this.list = list.cblist;}
var subProto = sub.prototype;
subProto.sub = function(){cb.remove();}

var EventLoop=function(list){
	object.prototype.tostring.call(list) ===['object array']?
	while(true){

	}
	:
}

var cb = new callbackList;


//实现



