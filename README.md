CMPUT404-assignment-websockets
==============================

CMPUT404-assignment-websockets

See requirements.org (plain-text) for a description of the project.

Make a shared state Websockets drawing program

Prereqs
=======
Create a virtual environment and install the required dependencies.

```bash
virtualenv venv --python=python3
source venv/bin/activate
pip install -r requirements.txt
```

Contributors / Licensing
========================

Generally everything is LICENSE'D under the Apache 2 license by Abram Hindle.

freetests.py is LICENSE'D under a BSD-like license:

From ws4py

Copyright (c) 2011-2014, Sylvain Hellegouarch, Abram Hindle
All rights reserved.

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions are met:

 * Redistributions of source code must retain the above copyright notice,
   this list of conditions and the following disclaimer.
 * Redistributions in binary form must reproduce the above copyright
   notice, this list of conditions and the following disclaimer in the
   documentation and/or other materials provided with the distribution.
 * Neither the name of ws4py nor the names of its contributors may be used
   to endorse or promote products derived from this software without
   specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS"
AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE
IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE
ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT OWNER OR CONTRIBUTORS BE
LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR
CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF
SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS
INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN
CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE)
ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE
POSSIBILITY OF SUCH DAMAGE.

Contributors
============

* Mark Galloway
* Abram Hindle
* Cole Mackenzie
* Kaixiang Zhang

Reference
========================

https://github.com/uofa-cmput404/cmput404-slides/blob/master/examples/ObserverExampleAJAX/server.py update/world/get_entity/clear functions which are inside the socket.py have been implemented based on the examples.

https://github.com/abramhindle/WebSocketsExamples/blob/master/chat.py clients/send_all/send_all_json/hello/read_ws/subscrible_socket are implemented based on the examples from the chat.py 

https://github.com/KaixiangCS/CMPUT404-assignment-ajax/blob/master/static/index.html wsSetup() was modified by sendJSONXMLHTTPRequest()

https://developer.mozilla.org/en-US/docs/Web/API/CanvasRenderingContext2D/arc learned how the arc method works so that I know how can I make changes to make the circle prettier.

https://developer.mozilla.org/zh-CN/docs/Web/API/XMLHttpRequest/setRequestHeader & https://developer.mozilla.org/en-US/docs/Web/API/XMLHttpRequest/responseLearn how to use the XMLHTTPRequest function to create a request and return Content-Type and Accept

//https://stackoverflow.com/questions/1484506/random-color-generator Copied a generate random color function to make the circle's color dynamic.

https://developer.mozilla.org/zh-CN/docs/Web/JavaScript/Reference/Global_Objects/Math/random Learned how to change the radius to achieve when people keep clicking one fix place it will become a circle with dynamic colors.
