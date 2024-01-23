# TV
Cette commande, écrit en Pascal (Turbo Pascal ou Free Pascal), permet de visualiser un fichier CSV comme dans un tableur (Table Viewer).

<h3>Syntaxe</h3>

<code>
TV fichier.CSV [-D caractere] [-DV nombre] [-LINES nombre] [-VGA]
</code>

<h3>Paramètres</h3>

<table>
  <tr>
    <th>Nom</th>
    <th>Description</th>
  </tr>
  <tr>
    <td>fichier.CSV</td>
    <td>Ce paramètre permet d'indiquer le nom du fichier a afficher.</td>
  </tr>
  <tr>
    <td>-D caractere</td>
    <td>Ce paramètre permet d'indiquer le caractère de séparation.</td>
  </tr>
  <tr>
    <td>-DV nombre</td>
    <td>Ce paramètre permet d'indiquer la valeur ASCII du caractère de séparation.</td>
  </tr>
  <tr>
    <td>-LINES nombre</td> 
    <td>Ce paramètre permet de forcer le nombre de ligne d''affichage spécifié.</td>
  </tr>
  <tr>
    <td>-VGA</td>
    <td>Ce paramètre permet de forcre le mode EGA/VGA (en mode DOS uniquement).</td>
  </tr>
</table>

<h3>Exemple</h3>

L'exemple suivant permnet d'afficher le contenu du fichier faker200.csv dans un terminal ayant 45 lignes d'affichages :

<code>
tv faker200.csv -lines 45
</code>

on obtiendra un résultat ressemblant à ceci :

![image](https://github.com/gladir/TV/assets/11842176/eb8e541b-a3ab-4561-8698-58a359bc971b)
