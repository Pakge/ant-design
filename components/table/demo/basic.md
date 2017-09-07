---
order: 0
title:
  en-US: Basic Usage
  zh-CN: 基本用法
---

## zh-CN

简单的表格，最后一列是各种操作。

## en-US

Simple table with actions.

````jsx
import { Table, Icon } from 'antd';

const columns = [{title:'index_name',dataIndex:'index_name',key:'index_name',}];

const data = [{
  key: '1',
  index_name: 'John Brown',
 
}, {
  key: '2',
  index_name: 'Jim Green'
 
}, {
  key: '3',
  index_name: 'Joe Black',
}];

ReactDOM.render(<Table columns={columns} dataSource={data} />, mountNode);
````
