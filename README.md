# logger
简单的日志操作

## 安装部署
npm install appcan-logger

## 使用
var logger = require("appcan-logger")('[app]');
logger.error('hello world');
logger.warn('hello world');
logger.info('hello world');
logger.log('hello world');

##日志等级
  'all', 'debug', 'info', 'warn', 'error', 'fatal', 'off'
  分别对应着1-7等级

  设置日志等级（只对设置后的日志起作用）
  require("appcan-logger").setLevel(4);

  清空日志（所有日志不输出，只对设置后的日志起作用）
  require("appcan-logger").clear();

	推荐使用等级
	'debug', 'info', 'warn', 'error'

	默认debug等级