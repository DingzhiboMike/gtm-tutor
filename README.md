# gtm-tutor

Скилл для Claude.

Тьютор-копилот по курсу GTM для PMM (пять блоков, модули M0–M13). Объясняет теорию в терминах курса, разбирает артефакты по рубрикам, штурмит гипотезы и помогает внедрять методы в работу. Домашку за ученика не пишет — ведёт по лестнице подсказок.

## Когда использовать

- Вопрос по модулю курса
- Проверить артефакт (VPC, канвас VP, дерево целей, launch brief и др.)
- Поштурмить сегменты, триггеры, VP, каналы

Не подходит для общих вопросов про JTBD или позиционирование вне контекста курса.

## Установка

**Claude Code.** Склонируйте репозиторий в папку скиллов:

```bash
git clone https://github.com/DingzhiboMike/gtm-tutor.git ~/.claude/skills/gtm-tutor
```

**Claude.ai / десктоп-приложение.** Скачайте репозиторий как ZIP (Code → Download ZIP) и загрузите его в настройках Claude, в разделе со скиллами.

После установки скилл включается сам, когда запрос подходит под его описание. Можно вызвать и явно — по имени `gtm-tutor`.

## Состав

- `SKILL.md`
- `references/instruments/channel-strategy.md`
- `references/instruments/dunford.md`
- `references/instruments/goal-tree.md`
- `references/instruments/launch-brief.md`
- `references/instruments/left-vpc.md`
- `references/instruments/lost-deals.md`
- `references/instruments/right-vpc-fit-map.md`
- `references/instruments/signals-review.md`
- `references/instruments/trigger-journey.md`
- `references/instruments/validated-canvas.md`
- `references/instruments/vp-canvas.md`
- `references/modules/m0-gtm.md`
- `references/modules/m1-jtbd-vpc.md`
- `references/modules/m10-buying-committee.md`
- `references/modules/m11-goal-tree.md`
- `references/modules/m12-launch.md`
- `references/modules/m13-growth.md`
- `references/modules/m2-appendix-quant.md`
- `references/modules/m2-insights-to-product.md`
- `references/modules/m3-customer-journey.md`
- `references/modules/m4-lost-deals.md`
- `references/modules/m5-positioning.md`
- `references/modules/m6-messaging.md`
- `references/modules/m7-validation-pricing.md`
- `references/modules/m8-channels-content.md`
- `references/modules/m9-sales-enablement.md`
- `references/thinking.md`

## Лицензия

[MIT](LICENSE)
