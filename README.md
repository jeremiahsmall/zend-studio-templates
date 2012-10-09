ZendStudio 9 Templates
=====================

The IDE tweaks that I like for my own use on new machines. Feel free to use them too. I'm using them with ZendStudio 9 and ZendFramework 2.

## PHP Editor Templates
Start typing the following key combinations and they code-hint to expand to the snippet that follows it.

To install, open Preferences > PHP > Editor > Templates and import the xml file.

### zddb

    \Zend\Debug\Debug::dump(${cursor});die();
    
### zddl

    $$debugLogger = new \Zend\Log\Logger();
    $$debugLogger->addWriter(new \Zend\Log\Writer\Stream('data/debug.log'));
    $$debugLogger->debug(${cursor});