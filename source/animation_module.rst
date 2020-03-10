The Animation Module
====================

The `AnimationModule` allows you to animate 3D objects that live in your assets directory.


Getting the Module into Your Project
------------------------------------
To be able to use the Animation module, we need to import it into our script.

.. code-block:: javascript
    
    const Animation = require('Animation');

Properties
----------

**samplers** are exposed values from your animation. These values can be of types: `Colors`, or `ScalarSamples` (an array of numbers).

You'll generally be using this property to recieve more information about easing methods you're using.

Read more about the values you can retrieve from the SamplerFactory `here <https://sparkar.facebook.com/ar-studio/learn/documentation/reference/animation_module/samplerfactory_class>`_.
