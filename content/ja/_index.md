---
title: "Regolith Linux"
linkTitle: "Regolith Linux"
---

{{< blocks/cover image_anchor="top" height="full" >}}

<h2 class="m-5">レゴリスは開発者のために何よりもシンプルな環境で、より効率のよい作業をしてもらいたく設計された、デスクトップ環境です。 Built on top of Ubuntu, GNOME, and i3, Regolith stands on a well-supported and consistent foundation.</h2>

<div class="row">
  <div class="col-sm-8 mb-5">{{< img "images/regolith-screenshot-intro.png" "Regolith Linux" >}}</div>
  <div class="col-sm-4">
    <div class="mx-auto">
    <a class="btn btn-lg btn-secondary mr-3 mb-4 rounded-pill" href="{{< ref "/download" >}}">
      Get Regolith <i class="fas fa-cloud-download-alt ml-2 "></i>
    </a>
    <a class="btn btn-lg btn-primary mr-3 mb-4" href="{{< ref "/docs" >}}">
      Learn More <i class="fas fa-book-reader ml-2"></i>
    </a>
    <a class="btn btn-lg btn-success mr-3 mb-4" href="https://opencollective.com/regolith/donate">
      Contribute <i class="fas fa-piggy-bank ml-2"></i>
    </a>
</div>
</div>
    <div class="mx-auto mt-5 pt-5">
      {{< blocks/link-down color="white" >}}
  </div>
{{< /blocks/cover >}}

<a name="td-block-1"><h3 class="text-center p-5" >ビジュアル</h3></a>

<div class="container mt-3">
  <div class="row pb-5">
    <div class="col-8 my-auto"><p>最初のログイン時にオーバーレイで（ <span class="text-nowrap"><span class="badge badge-warning">super</span> <span class="badge badge-warning">?</span></span>で常にトグル可）i3-wmで使用される主要キーバインディングを表示。</p></div>
    <div class="col-4 my-auto border rounded p-1">{{< img "images/screenshot-remontoire.png" "Shortcuts" >}}</div>
  </div>
  <div class="row pb-5">
    <div class="col-4 my-auto border rounded p-1">{{< img "images/screenshot-terminal.png" "Single Terminal" >}}</div>
    <div class="col-8 my-auto"><p>ターミナルで作業する場合には、<super>-<enter> で移動。</p></div>    
  </div>
  <div class="row pb-5">
    <div class="col-8 my-auto"><p><span class="text-nowrap"><span class="badge badge-warning">super</span> <span class="badge badge-warning">space</span></span> のグローバルアプリランチャで瞬時にどの画面からも使用しているプログラムを立ち上げ可能。</p></div>
    <div class="col-4 my-auto border rounded p-1">{{< img "images/screenshot-launcher.png" "Launcher" >}}</div>    
  </div>
  <div class="row pb-5">
    <div class="col-4 my-auto border rounded p-1">{{< img "images/screenshot-terminals.png" "Terminals" >}}</div>
    <div class="col-8 my-auto"><p>Need more terminals?  ターミナルを追加する場合には、垂直レイアウトと平行レイアウトの間をトグルするだけで新しいターミナルの追加ができる。？？？？修正必要？？？まずは<span class="text-nowrap"><span class="badge badge-warning">super</span> <span class="badge badge-warning">backspace</span></span>の後に  Navigate to windows positionally with <span class="text-nowrap"><span class="badge badge-warning">super</span> <span class="badge badge-warning">h</span> <span class="badge badge-warning">j</span> <span class="badge badge-warning">k</span> <span class="badge badge-warning">l</span></span>.</p></div>    
  </div>
  <div class="row pb-5">
    <div class="col-8 my-auto"><p>？？フローティングウィンドウモードを <span class="text-nowrap"><span class="badge badge-warning">super</span> <span class="badge badge-warning">F</span></span>でトグルする。 <span class="text-nowrap"><span class="badge badge-warning">super</span> <span class="badge badge-warning">r</span></span>でウィンドウのサイズ調整、<span class="text-nowrap"><span class="badge badge-warning">super</span> を押しながらマウスで移動させる。  Resize windows with <span class="text-nowrap"><span class="badge badge-warning">super</span> <span class="badge badge-warning">r</span></span> and move them around with the mouse by pressing <span class="badge badge-warning">super</span>.</p></div>
    <div class="col-4 my-auto border rounded p-1">{{< img "images/screenshot-float.png" "Window Float" >}}</div>    
  </div>
  <div class="row pb-5">
    <div class="col-4 my-auto border rounded p-1">{{< img "images/screenshot-gnome.png" "GNOME system admin" >}}</div>
    <div class="col-8 my-auto"><p>Gnome Flashbackは一貫したシンプルなシステム環境を提供します。 お使いのUIを調整、USBドライブをオートマウントし、ワイヤレスルーターに接続します。  <span class="text-nowrap"><span class="badge badge-warning">super</span> <span class="badge badge-warning">c</span></span>でコントロールパネルを起動。</p></div>    
  </div>
  <div class="row pb-5">
    <div class="col-8 my-auto"><p>Solarized などへの変換は <code>regolith-look</code>を使い簡単に。 regolithルックコマンドを使って、Solarizedなどへの変換がとても簡単。使用しているリソースのみを保存するので？？？？？？？</p></div>
    <div class="col-4 my-auto border rounded p-1">{{< img "images/regolith-screenshot-solarized.png" "Solarized" >}}</div>    
  </div>
  <div class="row pb-5">
    <div class="col-4 my-auto border rounded p-1">{{< img "images/screenshot-updates.png" "System Updates" >}}</div>
    <div class="col-8 my-auto"><p>Ubuntu上に構築されたRegolithは、最新の安定したシステムを提供。</p></div>    
  </div>
  <div class="row pb-5">
    <div class="col-8 my-auto"><p>Got a lot going on?  複数ウィンドウ同時進行でも迷子にならない。 <span class="text-nowrap"><span class="badge badge-warning">super</span> <span class="badge badge-warning">ctrl</span> <span class="badge badge-warning">space</span></span> もしくは <span class="text-nowrap"><span class="badge badge-warning">super</span> <span class="badge badge-warning">[0 - 19]</span></span>で瞬時に必要なウィンドウを見つける。</p></div>
    <div class="col-4 my-auto border rounded p-1">{{< img "images/screenshot-window.png" "Shortcuts" >}}</div>    
  </div>
  <div class="row pb-5">
    <div class="col-4 my-auto border rounded p-1">{{< img "images/screenshot-develop.png" "Window Management" >}}</div>
    <div class="col-8 my-auto"><p>スペースを無駄にしない。全ピクセルを使って作業したい。しかも画面レイアウトに時間を取りたくはない。</p></div>    
  </div>
  <div class="row pb-5">
    <div class="col-8 my-auto"><p>Desktop notifications do not compete for your attention, but rather can be managed via an on-screen dialog by pressing <span class="text-nowrap"><span class="badge badge-warning">super</span> <span class="badge badge-warning">n</span></span>.</p></div>
    <div class="col-4 my-auto border rounded p-1">{{< img "images/screenshot-notifications.png" "Notifications" >}}</div>    
  </div>
</div>

<a name="td-block-2"><h3 class="text-center p-5" ><i class="fas fa-info-circle pr-3"></i>What Makes Regolith Different</h3></a>

<div class="container">
<ul>
<li>Delivers a desktop with a functional yet minimal user interface that can be <a href="docs/customize/">customized</a> and expanded as needed.</li>
<li>Combines GNOME's system management features with <a href="https://i3wm.org/">i3-wm</a>'s productive workflow.</li>
<li>Enables new users a fast and fun way to try out a <a href="https://opensource.com/article/18/8/i3-tiling-window-manager">tiling window manager</a>.</li>
<li>Supports <a href="https://github.com/regolith-linux/regolith-desktop/wiki/Customize">easy customization</a> and <a href="https://www.reddit.com/r/unixporn">ricing</a> via a consistent <a href="https://github.com/regolith-linux/regolith-styles/blob/master/Xresources/root">Xresource configuration</a>.</li>
<li>Relies on <a href="https://snapcraft.io/store">Ubuntu's app store</a> and <a href="https://packages.ubuntu.com/">package repositories</a> for a large, high quality selection of software.</li>
<li>Built to be taken apart. <a href="docs/customize/components/">Swap in UI components</a> of your choosing easily.</li>
<li>Ships with a toggle overlay of basic <a href="docs/reference/keybindings/">keybindings</a> to make getting started easier.</li>
<li>Provides a <a href="https://github.com/regolith-linux/regolith-builder/blob/master/build.sh">build script</a> and <a href="https://github.com/regolith-linux/regolith-builder/blob/master/package-model-R1.3.json">package metadata</a> to allow users to easily fork the desktop environment and distribution.</li>
</ul>
</div>

<a name="td-block-3"><h3 class="text-center p-5" ><i class="fas fa-user-friends pr-3"></i>Thanks to...</h3></a>

<div class="container-fluid mb-3">
  <div class="row pl-0 align-top">
    <div class="col-3 col-md-0">
      Regolith is more curation than creation.  Here are some of the notable people and entities that produced unaffiliated work independently from which Regolith is based.
    </div>
    <div class="col-6 border rounded p-3">
      <div class="container">
        <div class="row">
          <div class="col-lg"><a href="https://i3wm.org">Michael Stapelberg</a> and <a href="https://github.com/Airblader/i3">Ingo Bürk</a></div>
          <div class="col-sm">Desktop UI</div>
        </div>
        <div class="row">
          <div class="col-lg"><a href="https://github.com/davatorium/rofi">Dave Davenport</a></div>
          <div class="col-sm">Desktop UI</div>
        </div>
        <div class="row">
          <div class="col-lg"><a href="https://github.com/yshui/compton">yshui</a></div>
          <div class="col-sm">Desktop UI</div>
        </div>
        <div class="row">
          <div class="col-lg"><a href="https://wiki.gnome.org/Projects/GnomeFlashback">Alberts Muktupāvels and Dmitry Shachnev</a></div>
          <div class="col-sm">Desktop UI</div>
        </div>
        <div class="row">
          <div class="col-lg"><a href="https://github.com/jcstr">Jesús Castro</a> and <a href="https://github.com/deuill">Alex Palaistras</a></div>
          <div class="col-sm">Desktop UI</div>
        </div>
        <div class="row">
          <div class="col-lg"><a href="https://github.com/vivien/i3blocks">Vivien Didelot</a></div>
          <div class="col-sm">Desktop UI</div>
        </div>
        <div class="row">
          <div class="col-lg"><a href="https://github.com/arcticicestudio">Arctic Ice Studio</a> and <a href="https://ethanschoonover.com/solarized/">Ethan Schoonover</a> and <a href="https://github.com/ayu-theme">Ayu Theme</a></div>
          <div class="col-sm">Colors</div>
        </div>
        <div class="row">
          <div class="col-lg"><a href="http://www.alastairreynolds.com/">Alastair Reynolds</a></div>
          <div class="col-sm">Proper Nouns</div>
        </div>
        <div class="row">
          <div class="col-lg"><a href="https://github.com/EliverLara/Nordic">Eliver Lara</a></div>
          <div class="col-sm">Theme</div>
        </div>
        <div class="row">
          <div class="col-lg"><a href="https://snwh.org/paper">Sam Hewitt</a></div>
          <div class="col-sm">Icons</div>
        </div>
        <div class="row">
          <div class="col-lg"><a href="http://wallpaper-site.webflow.io/">Psiu Puxa</a>,<a href="https://unsplash.com/photos/C0OD8OM-oM0">Lucas Bellator</a>, and <a href="https://unsplash.com/photos/xnqVGsbXgV4">Luca Bravo</a></div>
          <div class="col-sm">Artwork</div>
        </div>
        <div class="row">
          <div class="col-lg"><a href="https://launchpad.net/cubic">PJ Singh</a></div>
          <div class="col-sm">Infrastructure</div>
        </div>
        <div class="row">
          <div class="col-lg"><a href="https://canonical.com">Canonical</a> and <a href="https://github.com">GitHub</a></div>
          <div class="col-sm">Infrastructure</div>
        </div>
      </div>
    </div>
  </div>
</div>
