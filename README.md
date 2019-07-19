# proxies
A comprehensive list of CORS proxies.

This project is based on this awesome work of @jimmywarting: https://gist.github.com/jimmywarting/ac1be6ea0297c16c477e17f8fbe51347

## To do:

Order, clean and add this endpoints:

* https://api.allorigins.win/raw?url=
* https://yacdn.org/proxy/
* http://www.whateverorigin.org/get?url=
* https://test.cors.workers.dev/?
* https://universal-cors-proxy.glitch.me/
* https://jsonp.afeld.me/?callback=&url=
* http://coin-toss.herokuapp.com/
* https://crossorigin.me/
* https://cors-proxy.htmldriven.com/?url=
* https://cors-anywhere.herokuapp.com/
* https://api.codetabs.com/v1/proxy?quest=
* https://codetabs.com/cors-proxy/cors-proxy.html
* https://cors-proxy.htmldriven.com/?url=
* https://cors-anywhere.herokuapp.com/
* https://corsproxy.github.io/
* http://crossorigin.me/
* http://cors-proxy.htmldriven.com/?url= // necesita parsearse
* http://www.whateverorigin.org/get?url= // necesita parsearse // &callback=?
* https://cors-anywhere.herokuapp.com/
* https://cors.io/?
* http://dry-sierra-94326.herokuapp.com/
* https://thingproxy.freeboard.io/fetch/
* https://cors.now.sh/
* https://free-cors-proxy.herokuapp.com
* https://corsproxy.our.buildo.io
* http://www.corsify.me/
* http://gobetween.oklabs.org/pipe/
* http://cors.hyoo.ru/
* https://cors4js.appspot.com/?url=
* http://fuck-cors.com/?url=
* https://proxy-sauce.glitch.me/
* http://www.corsproxy.com/			
* http://goxcors.appspot.com/
* https://cors-proxy.taskcluster.net
* http://jsonp.herokuapp.com/
* http://anyorigin.com/go/?url=
* http://corsy.rs.af.cm/?get=
* https://crossproxy.me/
* https://galvanize-cors-proxy.herokuapp.com/
* https://cors-buster.now.sh/?href=
* https://jsfiddle.net/1d8cwqo0/1/
* https://jsfiddle.net/Ln47kyt2/3/

<table>
    <thead>
      <tr>
        <th>Service</th>
        <th>SSL</th>
        <th>status</th>
        <th>Response Type</th>
        <th>Allowed methods</th>
        <th>Allowed headers</th>
        <th>Exposed headers</th>
        <th>Follow redirect</th>
        <th>Streamable</th>
        <th>WebSocket</th>
        <th>Upload limit</th>
        <th>Download limit</th>
        <th>Country code</th>
        <th>Comments</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <!-- Service         --> <td><a href="https://github.com/Rob--W/cors-anywhere">cors-anywhere</a></td>
        <!-- SSL             --> <td align="center">✅</td>
        <!-- status          --> <td align="center">Mirrored</td>
        <!-- Response Type   --> <td align="center">Raw</td>
        <!-- Allowed Methods --> <td align="center">*</td>
        <!-- Allowed headers --> <td align="center">*</td>
        <!-- Exposed headers --> <td align="center">*</td>
        <!-- Follow redirect --> <td align="center" nowrap>Up to 5x</td>
        <!-- Streamable      --> <td align="center">❓</td>
        <!-- WebSocket       --> <td align="center">❓</td>
        <!-- Upload limit    --> <td align="center">❓</td>
        <!-- Download limit  --> <td align="center">❓</td>
        <!-- Country code    --> <td align="center">US</td>
        <!-- Comments        --> <td nowrap>Require Origin header</td>
      </tr>
      <tr>
        <!-- Service         --> <td><a href="https://corsproxy.github.io">crossorigin.me</a></td>
        <!-- SSL             --> <td align="center">✅</td>
        <!-- status          --> <td align="center">❓</td>
        <!-- Response Type   --> <td align="center">❓</td>
        <!-- Allowed Methods --> <td align="center">GET</td>
        <!-- Allowed headers --> <td align="center">❓</td>
        <!-- Exposed headers --> <td align="center">❓</td>
        <!-- Follow redirect --> <td align="center">❓</td>
        <!-- Streamable      --> <td align="center">❓</td>
        <!-- WebSocket       --> <td align="center">❓</td>
        <!-- Upload limit    --> <td align="center">2MB</td>
        <!-- Download limit  --> <td align="center">2MB</td>
        <!-- Country code    --> <td align="center">US</td>
        <!-- Comments        --> <td nowrap>Require Origin header</td>
      </tr>
      <tr hidden>
        <!-- Service         --> <td><a href="https://cors-proxy.htmldriven.com/">HTML Driven</a></td>
        <!-- SSL             --> <td align="center">✅</td>
        <!-- status          --> <td align="center">❓</td>
        <!-- Response Type   --> <td align="center">❓</td>
        <!-- Allowed Methods --> <td align="center">❓</td>
        <!-- Allowed headers --> <td align="center">❓</td>
        <!-- Exposed headers --> <td align="center">❓</td>
        <!-- Follow redirect --> <td align="center">❓</td>
        <!-- Streamable      --> <td align="center">❓</td>
        <!-- WebSocket       --> <td align="center">❓</td>
        <!-- Upload limit    --> <td align="center">❓</td>
        <!-- Download limit  --> <td align="center">❓</td>
        <!-- Country code    --> <td align="center">❓</td>
        <!-- Comments        --> <td nowrap></td>
      </tr>
      <tr>
        <!-- Service         --> <td><a href="https://walac.github.io/cors-proxy">Taskcluster</a></td>
        <!-- SSL             --> <td align="center">✅</td>
        <!-- status          --> <td align="center">❓</td>
        <!-- Response Type   --> <td align="center">❓</td>
        <!-- Allowed Methods --> <td align="center">*</td>
        <!-- Allowed headers --> <td align="center">❓</td>
        <!-- Exposed headers --> <td align="center">❓</td>
        <!-- Follow redirect --> <td align="center">❓</td>
        <!-- Streamable      --> <td align="center">❓</td>
        <!-- WebSocket       --> <td align="center">❓</td>
        <!-- Upload limit    --> <td align="center">❓</td>
        <!-- Download limit  --> <td align="center">❓</td>
        <!-- Country code    --> <td align="center">US</td>
        <!-- Comments        --> <td nowrap>All request must be made within the request body<br>Only whitelisted for taskcluster</td>
      </tr>
      <tr>
        <!-- Service         --> <td><a href="http://anyorigin.com">anyorigin</a></td>
        <!-- SSL             --> <td align="center">❌</td>
        <!-- status          --> <td align="center">❓</td>
        <!-- Response Type   --> <td align="center">jsonp</td>
        <!-- Allowed Methods --> <td align="center">GET</td>
        <!-- Allowed headers --> <td align="center">none</td>
        <!-- Exposed headers --> <td align="center">none</td>
        <!-- Follow redirect --> <td align="center">❓</td>
        <!-- Streamable      --> <td align="center">❌</td>
        <!-- WebSocket       --> <td align="center">❌</td>
        <!-- Upload limit    --> <td align="center">❌</td>
        <!-- Download limit  --> <td align="center">❓</td>
        <!-- Country code    --> <td align="center">US</td>
        <!-- Comments        --> <td nowrap></td>
      </tr>
      <tr>
        <!-- Service         --> <td><a href="repo">thingproxy</a></td>
        <!-- SSL             --> <td align="center">✅</td>
        <!-- status          --> <td align="center">❓</td>
        <!-- Response Type   --> <td align="center">❓</td>
        <!-- Allowed Methods --> <td align="center">*</td>
        <!-- Allowed headers --> <td align="center">❓</td>
        <!-- Exposed headers --> <td align="center">❓</td>
        <!-- Follow redirect --> <td align="center">❓</td>
        <!-- Streamable      --> <td align="center">❓</td>
        <!-- WebSocket       --> <td align="center">❓</td>
        <!-- Upload limit    --> <td align="center">100kb</td>
        <!-- Download limit  --> <td align="center">100kb</td>
        <!-- Country code    --> <td align="center">US</td>
        <!-- Comments        --> <td nowrap>Max 10 req/sec</td>
      </tr>
      <tr>
        <!-- Service         --> <td nowrap><a href="https://github.com/ripper234/Whatever-Origin">Whatever Origin</a></td>
        <!-- SSL             --> <td align="center">❌</td>
        <!-- status          --> <td align="center">❌</td>
        <!-- Response Type   --> <td align="center">jsonp</td>
        <!-- Allowed Methods --> <td align="center">GET</td>
        <!-- Allowed headers --> <td align="center">None</td>
        <!-- Exposed headers --> <td align="center">None</td>
        <!-- Follow redirect --> <td align="center">❓</td>
        <!-- Streamable      --> <td align="center">❌</td>
        <!-- WebSocket       --> <td align="center">❌</td>
        <!-- Upload limit    --> <td align="center">❓</td>
        <!-- Download limit  --> <td align="center">❓</td>
        <!-- Country code    --> <td align="center">US</td>
        <!-- Comments        --> <td nowrap></td>
      </tr>
      <tr>
        <!-- Service         --> <td><a href="https://cors.io/">cors.io</a></td>
        <!-- SSL             --> <td align="center">✅</td>
        <!-- status          --> <td nowrap align="center">Only code mirror</td>
        <!-- Response Type   --> <td align="center">Raw</td>
        <!-- Allowed Methods --> <td align="center">GET, HEAD</td>
        <!-- Allowed headers --> <td align="center">❓</td>
        <!-- Exposed headers --> <td align="center">❓</td>
        <!-- Follow redirect --> <td align="center">✅</td>
        <!-- Streamable      --> <td align="center">❓</td>
        <!-- WebSocket       --> <td align="center">❓</td>
        <!-- Upload limit    --> <td align="center">❓</td>
        <!-- Download limit  --> <td align="center">❓</td>
        <!-- Country code    --> <td align="center">US</td>
        <!-- Comments        --> <td nowrap></td>
      </tr>
      <tr>
        <!-- Service         --> <td><a href="https://github.com/okfn/gobetween">Go Between</a></td>
        <!-- SSL             --> <td align="center">✅</td>
        <!-- status          --> <td align="center">❓</td>
        <!-- Response Type   --> <td align="center">❓</td>
        <!-- Allowed Methods --> <td align="center">❓</td>
        <!-- Allowed headers --> <td align="center">❓</td>
        <!-- Exposed headers --> <td align="center">❓</td>
        <!-- Follow redirect --> <td align="center">❓</td>
        <!-- Streamable      --> <td align="center">❓</td>
        <!-- WebSocket       --> <td align="center">❓</td>
        <!-- Upload limit    --> <td align="center">❓</td>
        <!-- Download limit  --> <td align="center">❓</td>
        <!-- Country code    --> <td align="center">❓</td>
        <!-- Comments        --> <td nowrap></td>
      </tr>
      <tr>
        <!-- Service         --> <td><a href="https://github.com/acidsound/goxcors">goxcors</a></td>
        <!-- SSL             --> <td align="center">✅</td>
        <!-- status          --> <td align="center">Allways 200</td>
        <!-- Response Type   --> <td align="center">Raw</td>
        <!-- Allowed Methods --> <td align="center">*</td>
        <!-- Allowed headers --> <td align="center">*</td>
        <!-- Exposed headers --> <td align="center">None</td>
        <!-- Follow redirect --> <td align="center">✅</td>
        <!-- Streamable      --> <td align="center">❓</td>
        <!-- WebSocket       --> <td align="center">❓</td>
        <!-- Upload limit    --> <td align="center">❓</td>
        <!-- Download limit  --> <td align="center">❓</td>
        <!-- Country code    --> <td align="center">US</td>
        <!-- Comments        --> <td nowrap>
                                   POST type is limited to x-www-form-urlencoded<br>
                                   Have a werd api<br>
                                   Response Type is Allways text/html
                                 </td>
      </tr>
      <tr>
        <!-- Service         --> <td><a href="https://yacdn.org">YaCDN</a></td>
        <!-- SSL             --> <td align="center">✅</td>
        <!-- status          --> <td align="center">Not mirrored</td>
        <!-- Response Type   --> <td align="center">Raw</td>
        <!-- Allowed Methods --> <td align="center">GET</td>
        <!-- Allowed headers --> <td align="center">None</td>
        <!-- Exposed headers --> <td align="center">❌</td>
        <!-- Follow redirect --> <td align="center">Up to 22x</td>
        <!-- Streamable      --> <td align="center">❓</td>
        <!-- WebSocket       --> <td align="center">❓</td>
        <!-- Upload limit    --> <td align="center">❓</td>
        <!-- Download limit  --> <td align="center">❓</td>
        <!-- Country code    --> <td align="center">FR</td>
        <!-- Comments        --> <td nowrap>CDN, ignores browsers headers</td>
      </tr>
      <tr>
        <!-- Service         --> <td><a href="https://allorigins.win">All Origins</a></td>
        <!-- SSL             --> <td align="center">✅</td>
        <!-- status          --> <td align="center">Only code in json</td>
        <!-- Response Type   --> <td align="center">Json, jsonp, Raw</td>
        <!-- Allowed Methods --> <td align="center">*</td>
        <!-- Allowed headers --> <td align="center">❌</td>
        <!-- Exposed headers --> <td align="center">None</td>
        <!-- Follow redirect --> <td align="center">✅</td>
        <!-- Streamable      --> <td align="center">❓</td>
        <!-- WebSocket       --> <td align="center">❓</td>
        <!-- Upload limit    --> <td align="center">❓</td>
        <!-- Download limit  --> <td align="center">❓</td>
        <!-- Country code    --> <td align="center">US</td>
        <!-- Comments        --> <td nowrap>When using raw you loose status information</td>
      </tr>
      <tr>
        <!-- Service         --> <td><a href="https://www.test-cors.org/">Test CORS</a></td>
        <!-- SSL             --> <td align="center">❓</td>
        <!-- status          --> <td align="center">❓</td>
        <!-- Response Type   --> <td align="center">❓</td>
        <!-- Allowed Methods --> <td align="center">❓</td>
        <!-- Allowed headers --> <td align="center">❓</td>
        <!-- Exposed headers --> <td align="center">❓</td>
        <!-- Follow redirect --> <td align="center">❓</td>
        <!-- Streamable      --> <td align="center">❓</td>
        <!-- WebSocket       --> <td align="center">❓</td>
        <!-- Upload limit    --> <td align="center">❓</td>
        <!-- Download limit  --> <td align="center">❓</td>
        <!-- Country code    --> <td align="center">❓</td>
        <!-- Comments        --> <td nowrap></td>
      </tr>
      <tr>
        <!-- Service         --> <td><a href="https://github.com/Zibri/cloudflare-cors-anywhere">Cloudflare Cors Anywhere</a></td>
        <!-- SSL             --> <td align="center">✅</td>
        <!-- status          --> <td align="center">Only code mirror (not statusText)</td>
        <!-- Response Type   --> <td align="center">Raw</td>
        <!-- Allowed Methods --> <td align="center">*</td>
        <!-- Allowed headers --> <td align="center">All but expect <a href="https://developer.mozilla.org/en-US/docs/Glossary/Forbidden_header_name">Forbidden headers</a></td>
        <!-- Exposed headers --> <td align="center">none</td>
        <!-- Follow redirect --> <td align="center">✅</td>
        <!-- Streamable      --> <td align="center">❌</td>
        <!-- WebSocket       --> <td align="center">❓</td>
        <!-- Upload limit    --> <td align="center">none</td>
        <!-- Download limit  --> <td align="center">none</td>
        <!-- Country code    --> <td align="center">❓</td>
        <!-- Comments        --> <td nowrap>100,000 requests/day 1,000 requests/10 minutes</td>
      </tr>
    </tbody>
  </table>

<!-- code used for some testing
    const services = [
    /*
    {
      proxy: 'https://cors-anywhere.herokuapp.com/',
      fetch(url, opts = {}) {
        return new Request(this.proxy + url, opts)
      }
    },

    {
      proxy: 'https://crossorigin.me/',
      fetch(url, opts = {}) {
        return new Request(this.proxy + url, opts)
      }
    },

    {
      proxy: 'https://cors.io/?',
      fetch(url, opts = {}) {
        return fetch(new Request(this.proxy + url, opts))
      }
    },

    {
      proxy: 'https://goxcors.appspot.com/cors',
      async fetch(url, opts = {}) {

        if (!opts.method) opts.method = 'GET'
        else opts.method = opts.method.toUpperCase()
        
        opts.headers = new Headers(opts.headers || {})
        
        if (opts.body instanceof FormData) {
          throw new Error('FormData not supported')
        }
        
        const proxyURL = new URL(this.proxy)
        const proxyOpts = {
          method: opts.method,
          body: opts.body || null
        }

        proxyURL.searchParams.set('url', url)
        proxyURL.searchParams.set('method', opts.method)
        
        if (opts.headers) {
          for (let header of opts.headers) {
            proxyURL.searchParams.append('header', `${header[0]}|${header[1]}`)
          }
        }
        
        return fetch(new Request(proxyURL, proxyOpts)).then(e => {
          return (e)
        })
      }
    }

    */

    {
      proxy: 'https://api.allorigins.win/raw',
      fetch(url, opts = {}) {
        const proxyURL = new URL(this.proxy)
        proxyURL.searchParams.set('url', url)
        return fetch(proxyURL, opts)
      }
    }

    ];




    (async () => {

    for (let service of services) {
      console.log('testing', service.proxy)

      { // simplestiest test
        const res = await service.fetch('https://httpbin.org/get')
        console.assert(res.ok, `expected ${service.proxy} to at least work`)
        console.assert(res.headers.get('X-Final-Url') === 'https://httpbin.org/get', 'expected to expose all headers')
      }

      { // Mirrors status code
        const res = await service.fetch('https://httpbin.org/status/418')
        console.assert(res.status === 418, `expected ${service.proxy} to respond with same status`)
        console.assert(res.statusText === `I'm a Teapot`, `expected ${service.proxy} to respond with statusText`)
      }
      
      try { // Should allow POST method
        const fd = new FormData()
        fd.append('foo', 'bar')
        
        const res = service.fetch('https://httpbin.org/post', { method: 'POST', body: fd })
        const json = await res.json()
        console.assert(json.form.foo === 'bar', 'expected form to work')
      } catch (err) { console.error('failed to post') }
      
      { // Should allow binary method
        const res = await service.fetch('https://httpbin.org/image', { headers: { accept: 'image/png'} })
        const data = await res.arrayBuffer()
        const sha = await crypto.subtle.digest('SHA-256', data)
        const expected = '84263024555592272207325284472171668111918210017419228141134824915811020185119216193'
        const result = new Uint8Array(sha).join('')
        console.assert(result === expected, 'expected req headers + binary response to work')
      }

      { // Should follow redirect
        const res = await service.fetch('https://httpbin.org/relative-redirect/3')
        const json = await res.json()
        console.assert(json.url === 'https://httpbin.org/get', 'expected to follow redirect')
      }  
      
      { // can avoid follow
        const res = await service.fetch('https://httpbin.org/relative-redirect/6', { redirect: 'manual' })
        console.assert(await res.text() === '', 'expected response to be empty')
      }
      
    }
    console.log('done')
    })()
-->
