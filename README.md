OVH (extension Omeka)
=====================


Sommaire
-------

Cette extension pour [Omeka] permet d'utiliser le serveur partagé d'OVH et d'y
créer les images dérivées. Il ajoute simplement une bibliothèque. Il est utilisé
pour la [bibliothèque des phares].


Installation
------------

Uncompress files and rename plugin folder "ImageOvh".

Then install it like any other Omeka plugin. The plugin has no configuration.

Dans application/config/config.ini, ajouter :

fileDerivatives.strategy = "Ovh_ExternalImageMagick"
fileDerivatives.strategyOptions.convert_path = "convert"


Warning
-------

Use it at your own risk.

It's always recommended to backup your files and database regularly so you can
roll back if needed.


Troubleshooting
---------------

No issue. Simply update when Ovh is updated.


License
-------

This plugin is published under the [CeCILL v2.1] licence, compatible with
[GNU/GPL] and approved by [FSF] and [OSI].

In consideration of access to the source code and the rights to copy, modify and
redistribute granted by the license, users are provided only with a limited
warranty and the software's author, the holder of the economic rights, and the
successive licensors only have limited liability.

In this respect, the risks associated with loading, using, modifying and/or
developing or reproducing the software by the user are brought to the user's
attention, given its Free Software status, which may make it complicated to use,
with the result that its use is reserved for developers and experienced
professionals having in-depth computer knowledge. Users are therefore encouraged
to load and test the suitability of the software as regards their requirements
in conditions enabling the security of their systems and/or data to be ensured
and, more generally, to use and operate it in the same conditions of security.
This Agreement may be freely reproduced and published, provided it is not
altered, and that no provisions are either added or removed herefrom.


Contact
-------

Current maintainers:

* Daniel Berthereau (see [Daniel-KM])

First version of this plugin has been built for [École des Ponts ParisTech].


Copyright
---------

* Copyright Daniel Berthereau, 2014


[Omeka]: https://omeka.org "Omeka.org"
[bibliothèque des phares]: http://bibliothequedesphares.fr
[CeCILL v2.1]: http://www.cecill.info/licences/Licence_CeCILL_V2.1-en.html "
[GNU/GPL]: https://www.gnu.org/licenses/gpl-3.0.html
[FSF]: https://www.fsf.org
[OSI]: http://opensource.org
[Daniel-KM]: https://github.com/Daniel-KM "Daniel Berthereau"
[École des Ponts ParisTech]: http://bibliotheque.enpc.fr