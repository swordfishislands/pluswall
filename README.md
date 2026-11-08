# PlusWall

**A responsive, and configurable, Google+ inspired theme for [Blogger](https://www.blogger.com/)**.

![PlusWall post wall with three columns and mixed image and text posts](screenshots/post-wall.png)


## Features

- Responsive, multi-column post wall with full-width images and natural-height cards.
- Native Blogger **jump breaks** for controlling how much of a post appears in the wall, with a *See more* link.
- Individual post pages with Blogger's built-in threaded comments and reply controls.
- Cover banner configured through Blogger's **Header** gadget, with title, description, and profile photograph.
- Contributor avatars are sourced from their Blogger profiles.
- Navigation managed with Blogger's native **Link List** gadget; a Home link is generated automatically.
- Search, labels, post permalinks, and standard Blogger pagination.

### Mobile and comments

<img src="screenshots/mobile-banner.png" alt="PlusWall mobile banner and navigation on a development blog" width="360">

<img src="screenshots/comments.png" alt="PlusWall threaded comments with author avatars and timestamps" width="490">


## To Install

Download **[`PlusWall_1.0.xml`](PlusWall_1.0.xml)** from this repository, or get the XML file from the latest [GitHub release](../../releases/latest).

1. In **Blogger → Theme**, back up your existing theme first using the theme menu's **Backup** option.
2. In the same menu, select **Restore** and upload `PlusWall_1.0.xml`.
3. Open **Blogger → Layout → Header**. Set your cover image and select **Behind title and description**. Header image assumed to be **1240 x 405 px**
4. Under **Layout → About Me**, enable/configure the Blogger Profile gadget and make sure your Blogger profile has a photo. This supplies the main profile image; individual posts use their authors' profile images.
5. Open **Layout → Navigation Links → Edit** to manage the Link List entries. **Home** is automatic, so you do not need to add it. To link to a label, use its label URL, for example `/search/label/Art`.
6. Check the home page, an individual post, comments, labels, and the mobile layout before retiring your previous theme.

**Important:** Blogger stores some gadget settings in the theme XML. Reinstalling or upgrading a theme may change the Header and Link List settings. Always keep a backup of a working installation before replacing the theme.

## Origins, Attribution, and License

PlusWall was developed by customizing and substantially restyling Google's **Blogger Emporio** theme. The original Blogger widget framework and portions of the widget markup remain. PlusWall is an **unofficial** theme, not made by or affiliated with Google.

The original PlusWall contributions are offered under the **MIT License**, to the extent the contributors hold copyright or other rights to license them. See [`LICENSE`](LICENSE). This is **not** a blanket claim of ownership or an MIT license for Google's inherited Blogger code.

The XML also includes **Normalize.css 3.0.1**, licensed under MIT by Nicolas Gallagher and Jonathan Neal. See [`THIRD_PARTY_NOTICES.md`](THIRD_PARTY_NOTICES.md) and [`licenses/normalize.css-MIT.txt`](licenses/normalize.css-MIT.txt).

The original Emporio code's separate redistribution terms have not been independently verified. The included credits and limited-scope MIT grant should not be interpreted as resolving that question.
