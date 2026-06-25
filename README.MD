# DevOps Monitoring

## Project Overview

## Архитектура
                        Browser
                           │
        ┌──────────────────┴──────────────────┐
        │                                     │
 localhost:8080                        localhost:3000
        │                                     │
     HAProxy                            Grafana
        │                                   ▲
   ┌────┴────┐                              │
   │         │                         Prometheus
nginx1    nginx2                    ▲            ▲
                                    │            │
                              cAdvisor    Node Exporter
## Технологии

## Структура проекта

## Features

## Стек мониторинга

## How to Run

## Demo

## Будущие улучшения
