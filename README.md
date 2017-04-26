# Tootools


## Purpose

Tootools is a web services framework design to simplify construction of SaaS software as much as backend for remote app, 
embed in a smartphone or installed on computer.

It define a simple meta model of components called __Tool__ that can be deployed on the fly and combined together. It
offer a basic mechanism to interpret __Request__ with data provided by language implementation. It give a solution of
communication layer between tools deployed on the same environment.

## Structure

A __Tool__ is composed of __Controller__ that manipulate specific __Ressource__, and __Service__ that can be called by
a remote client.


## User Account

The framework is organized around an environment that offer light __Account__ support with __Profile__, __Permission__
and __Option__.


## Session

Each __Request__ can be integrated in a full __Session__ context or in a totally anonymous process depending of the 
__Service__ requested by the remote client.


## Tokens

__Account__ can be provisioned with __Token__ to limit some capabilities of account and services usage. A payment
system could be for example implemented with a particular service to provide __Token__ to remote client.


## Multi-language

Tootools support a classic mechanism of multi language string and adapt messages according to remote client language.
