.. _index:

.. title:: PocketMine-MP

.. image:: https://gitee.com/mibino233/pmmp-zh-cn-docs-files/raw/master/PocketMine-h.png
   :align: center

|

.. raw:: html

   <p align="center">
	<a href="https://github.com/pmmp/PocketMine-MP/actions/workflows/main.yml"><img src="https://github.com/pmmp/PocketMine-MP/workflows/CI/badge.svg" alt="CI" /></a>
	<a href="https://github.com/pmmp/PocketMine-MP/releases/latest"><img alt="GitHub release (latest SemVer)" src="https://img.shields.io/github/v/release/pmmp/PocketMine-MP?label=release&sort=semver"></a>
	<a href="https://hub.docker.com/r/pmmp/pocketmine-mp"><img src="https://img.shields.io/docker/v/pmmp/pocketmine-mp?logo=docker&label=image" alt="Docker image version (latest semver)" /></a>
	<a href="https://discord.gg/bge7dYQ"><img src="https://img.shields.io/discord/373199722573201408?label=discord&color=7289DA&logo=discord" alt="Discord" /></a>
	<br>
	<a href="https://github.com/pmmp/PocketMine-MP/releases"><img alt="GitHub all releases" src="https://img.shields.io/github/downloads/pmmp/PocketMine-MP/total?label=downloads%40total"></a>
	<a href="https://github.com/pmmp/PocketMine-MP/releases/latest"><img alt="GitHub release (latest by SemVer)" src="https://img.shields.io/github/downloads/pmmp/PocketMine-MP/latest/total?sort=semver"></a>
   </p>

.. rst-class:: center

    `Plugin Repository <https://poggit.pmmp.io/plugins>`_ • `Forums <https://forums.pmmp.io>`_ • `Discord <https://discord.gg/bge7dYQ>`_ • `Source Code <https://github.com/pmmp>`_

PocketMine MP是Minecraft：Bedrock系列Minecraft版本（包括Android、iOS、W10和其他版本）的高度可定制且开源的服务端。

它有什么特点？
===========================
- 一个强大的插件API，它允许您比任何竞争服务器实现（包括官方的香草服务端）更容易、更广泛地扩展和定制服务器。
- 多世界支持，允许您为玩家提供更丰富的游戏体验，而无需将其转移到其他服务器节点。
- 性能适合容纳100多名玩家（取决于硬件，请参阅:ref:`requirements`部分）。
- 持续更新以支持最新的Minecraft版本。PocketMine MP拥有与新Minecraft版本兼容的任何自定义服务器中最长和最好的跟踪记录。
.. note::

   PocketMine-MP is **NOT** a complete vanilla server, and it doesn't have some features you would find in the vanilla game.

   If you just want to play *survival multiplayer* and don't care about *plugins*, you should consider using the `official Minecraft: Bedrock server software <https://minecraft.net/download/server/bedrock>`_ instead of using PocketMine-MP.

.. toctree::
    :maxdepth: 1
    :caption: Getting Started

    installation
    basic-usage
    configuration
    plugins
    resourcepacks
    permissions
    contact
    links

.. toctree::
    :caption: Frequently Asked Questions & Common Issues
    :maxdepth: 1
    :glob:

    faq/installation
    faq/connecting
    faq/playing
    faq/plugins
    faq/about

.. toctree::
    :glob:
    :maxdepth: 1
    :caption: Issues, Bugs and Crashes

    issues/*

.. toctree::
    :caption: Developer Resources
    :maxdepth: 1

    developer-resources
