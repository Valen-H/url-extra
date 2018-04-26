# url-extra  
 ## An extension of the builtin `url` module.  
  
  protocol: 'http:',  
  slashes: true,  
  auth: 'user:pass',  
  host: 'host.com:8080',  
  port: '8080',  
  hostname: 'host.com',  
  hash: '#hash',  
  search: '?query=string',  
  query: { query: 'string' },  
  pathname: '/p/a/t/h',  
  path: '/p/a/t/h?query=string',  
  href: 'http://user:pass@host.com:8080/p/a/t/h?query=string#hash',  
  protocolraw: 'http',  
  protocolfull: 'http://',  
  hashraw: 'hash',  
  autharray: [ 'user', 'pass' ],  
  querystringraw: 'query=string',  
  queryraw: { query: 'string' },  
  querystring: 'query=string',  
  pathobject: { root: '/', dir: '/p/a/t', base: 'h', ext: '', name: 'h' },  
  file: '/h',  
  fileraw: 'h',  
  filename: 'h',  
  extension: '',  
  extensionfull: '',  
  directory: '/p/a/t'  
  
> **By editing one of the properties of the Url object returned by url.parse, the whole object gets rebuilded!**