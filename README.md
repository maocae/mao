## Mao Engine WIP
A simple html view template engine. 

### Why i made this ?
When i made this, i really inspired by how php templating engine work, especially laravel blade engine. But sadly, to use that engine outside of laravel ecosystem, its quite tricky and 
require some bootstrapping (as i know, CMIIW). Thats why i start made my own templating engine, with a hope that this engine can works on many php project without many
setup.


### MVP First Draft
#### Functional Requirements
1. Execute PHP Code inside the view file
2. Perform looping
3. Perform conditional rendering
4. Render safe and unsafe content from variable
5. Cached generated view


#### Possible Keyword
- @php
- @if( condition ) statements @endif
- @for( condition ) statements @endfor
- @while( condition ) stataments @endwhile
- {{ variable }}
- @block( block name)
- @section( block name ) contents @endsection
- {!! escaped variable !!}


#### What might added
- Translation
- More complex rendering
