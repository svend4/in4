# in4

Серия технических исследований: **домашние AI-кластеры для локального LLM-инференса** (февраль 2026).

## Содержание серии

### Основная серия

| # | Файл | Тема |
|---|------|------|
| 0 | [comparison.html](comparison.html) | Apple Silicon vs x86 PC: сравнение для локального AI |
| 1 | [clustering.html](clustering.html) | Кластеризация: объединение компьютеров для AI |
| 2 | [clustering-part2.html](clustering-part2.html) | CXL, типы параллелизма, бенчмарки |
| 3 | [clustering-part3.html](clustering-part3.html) | Практическое руководство по кластеризации |
| 4 | [high-bandwidth-minipc-ru.html](high-bandwidth-minipc-ru.html) | Высокоскоростные мини-ПК (Strix Halo, DGX Spark) |
| 5 | [sbc-clusters-guide-ru.html](sbc-clusters-guide-ru.html) | Кластеры на одноплатных компьютерах (Raspberry Pi, Orange Pi) |
| 6 | [prima-cpp-minipc-guide-ru.html](prima-cpp-minipc-guide-ru.html) | prima.cpp: распределённый инференс для домашних кластеров |
| 7 | [favorites-prima-cpp-ru.html](favorites-prima-cpp-ru.html) | Все фавориты серии: финальная переоценка через prima.cpp |

### Технические руководства

| Файл | Тема |
|------|------|
| [prima-cpp-vulkan-porting-guide.html](prima-cpp-vulkan-porting-guide.html) | Prima.cpp + Vulkan: полное руководство по портированию |
| [prima-vulkan-port.html](prima-vulkan-port.html) | Vulkan-порт: альтернативное руководство |
| [tesla-zluda-vps-prima-cpp-ru.html](tesla-zluda-vps-prima-cpp-ru.html) | Tesla GPU + ZLUDA + VPS с prima.cpp |

### Расширенная серия (продолжение)

| # | Файл | Тема |
|---|------|------|
| 8 | [networking-deep-dive-ru.html](networking-deep-dive-ru.html) | Сетевая инфраструктура для AI-кластеров: RDMA, 10GbE, оптимизация TCP |
| 9 | [model-quantization-guide-ru.html](model-quantization-guide-ru.html) | Выбор моделей, квантизация и оптимизация инференса |
| 10 | [production-deployment-ru.html](production-deployment-ru.html) | Продакшн-развёртывание: мониторинг, автоматизация, API |
| 11 | [cost-performance-calculator-ru.html](cost-performance-calculator-ru.html) | Калькулятор стоимости и производительности всех конфигураций |

## Темы

- Распределённый LLM-инференс (llama.cpp, prima.cpp, EXO, distributed-llama)
- Кластеризация: pipeline, tensor, PRP (Piped-Ring Parallelism)
- Аппаратное обеспечение: Apple Silicon, AMD Strix Halo, NVIDIA, SBC
- Сетевая инфраструктура: Ethernet, Thunderbolt 5, RDMA, RoCE
- Квантизация моделей: GGUF, Q4_K_M, IQ, speculative decoding
- Vulkan GPU backend для кросс-платформенного ускорения
- Продакшн: systemd, Docker, Prometheus, Grafana, API

## Технологии

- **Фреймворки:** llama.cpp, prima.cpp, EXO, distributed-llama, Ollama
- **GPU API:** CUDA, Vulkan, Metal, ROCm
- **Железо:** Raspberry Pi 5, Orange Pi 5, Mac Mini M4, Framework Desktop, DGX Spark, Tesla P40
- **Мониторинг:** Prometheus, Grafana, Node Exporter
- **Автоматизация:** systemd, Docker Compose, Ansible

## Источники

- arXiv:2504.08791 (prima.cpp — Li et al.)
- arXiv:2511.07425 (LLM на SBC)
- Jeff Geerling (Pi-кластеры)
- distributed-llama (b4rtaz)
- Raspberry Pi Foundation
- ServeTheHome, TinyComputers.io

---
*Данные актуальны на февраль 2026.*
