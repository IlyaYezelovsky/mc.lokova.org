---
title: 配置文件
layout: default
---

**leaves.yml**（[前往 Leaves 官网查看说明](https://docs.leavesmc.org/zh_Hans/leaves/reference/configuration)）

```yaml
# Configuration file for Leaves.

config-version: 6
settings:
  protocol:
    chat-image-protocol: true
    rei-server-protocol: true
    appleskin:
      protocol: true
      sync-tick-interval: 20
    pca:
      pca-sync-protocol: false
      pca-sync-player-entity: OPS
    servux:
      litematics:
        enable: true
        max-nbt-size: 2147483647
      hud-logger-protocol: true
      hud-enabled-loggers:
      - TPS
      - MOB_CAPS
      hud-update-interval: 1
      hud-metadata-protocol: true
      hud-metadata-protocol-share-seed: true
      structure-protocol: true
      entity-protocol: true
    bladeren:
      protocol: true
      mspt-sync-protocol: false
      mspt-sync-tick-interval: 20
    syncmatica:
      enable: false
      quota: false
      quota-limit: 40000000
    bbor-protocol: false
    jade-protocol: true
    alternative-block-placement: NONE
    xaero-map-protocol: true
    xaero-map-server-id: 1506114546
    leaves-carpet-support: true
  misc:
    chat-command-max-length: 32767
    auto-update:
      download-source: application
      allow-experimental: true
      enable: false
      time:
      - '14:00'
      - '2:00'
    extra-yggdrasil-service:
      enable: true
      login-protect: true
      urls:
      - https://littleskin.cn/api/yggdrasil
    disable-method-profiler: true
    no-chat-sign: true
    dont-respond-ping-before-start-fully: true
    server-lang: zh_cn
    server-mod-name: Leaves
    bstats-privacy-mode: false
    force-minecraft-command: true
    leaves-packet-event: true
  fix:
    vanilla-end-void-rings: true
    collision-behavior: BLOCK_SHAPE_VANILLA
    vanilla-fluid-pushing: true
    vanilla-display-name: true
    vanilla-portal-handle: false
    vanilla-hopper: false
  modify:
    hopper-counter:
      enable: true
      unlimited-speed: true
    shulker-box:
      stackable-shulker-boxes: 64
      same-nbt-stackable: true
    movable-budding-amethyst: true
    exp-orb-absorb-mode: FAST
    disable-vault-blacklist: true
    fakeplayer:
      in-game:
        always-send-data: true
        skip-sleep-check: true
        spawn-phantom: false
        tick-type: NETWORK
        simulation-distance: -1
        enable-locator-bar: false
      manual-save-and-load: true
      cache-skin: true
      enable: true
      unable-fakeplayer-names:
      - player-name
      limit: 2147483647
      prefix: ''
      suffix: ''
      resident-fakeplayer: true
      open-fakeplayer-inventory: false
      regen-amount: 1.0
      use-action: true
      modify-config: true
    elytra-aeronautics:
      no-chunk-load: true
      no-chunk-height: 256.0
      no-chunk-speed: -1.0
      message: true
      message-start: 鞘翅飞行高度达到256，停止区块加载．感谢你为减轻服务器负荷作出的贡献．
      message-end: 鞘翅飞行高度降低到256以下，继续区块加载．感谢你为减轻服务器负荷作出的贡献．
    redstone-shears-wrench: true
    spectator-dont-get-advancement: true
    stick-change-armorstand-arm-status: true
    snowball-and-egg-can-knockback-player: false
    flatten-triangular-distribution: true
    player-operation-limiter: false
    renewable-elytra: 0.05
    force-void-trade: true
    mc-technical-survival-mode: true
    return-nether-portal-fix: true
    use-vanilla-random: true
    fix-update-suppression-crash: true
    bedrock-break-list: true
    disable-distance-check-for-use-item: true
    no-feather-falling-trample: true
    shared-villager-discounts: false
    disable-check-out-of-order-command: true
    despawn-enderman-with-block: false
    creative-no-clip: false
    shave-snow-layers: true
    disable-packet-limit: true
    lava-riptide: true
    no-block-update-command: false
    no-tnt-place-update: false
    container-passthrough: false
    avoid-anvil-too-expensive: true
    bow-infinity-fix: true
    spider-jockeys-drop-gapples: 1.0
    renewable-deepslate: true
    renewable-sponges: true
    renewable-coral: EXPANDED
    minecraft-old:
      old-raid-behavior: true
      keep-leash-connect-when-use-firework: true
      tnt-wet-explosion-no-item-damage: true
      old-projectile-explosion-behavior: true
      ender-dragon-part-can-use-end-portal: false
      spawn-invulnerable-time: true
      old-zombie-piglin-drop: true
      old-zombie-reinforcement: false
      tripwire-and-hook-behavior:
        string-tripwire-hook-duplicate: true
        tripwire-behavior: MIXED
      void-trade: true
      disable-item-damage-check: true
      old-throwable-projectile-tick-order: true
      old-hopper-suck-in-behavior: false
      block-updater:
        sound-update-suppression: false
        redstone-ignore-upwards-update: false
        old-block-remove-behaviour: false
        instant-block-updater-reintroduced: true
        cce-update-suppression: false
      allow-anvil-destroy-item-entities: false
      disable-LivingEntity-ai-step-alive-check: false
      disable-gateway-portal-entity-ticking: true
      allow-grindstone-overstacking: true
      allow-entity-portal-with-passenger: true
      shears-in-dispenser-can-zero-amount: true
      villager-infinite-discounts: true
      copper-bulb-1gt-delay: false
      crafter-1gt-delay: false
      zero-tick-plants: false
      rng-fishing: true
  performance:
    equipment-tracking: false
    sleeping-block-entity: false
    optimized-dragon-respawn: false
    dont-send-useless-entity-packets: true
    enable-suffocation-optimization: true
    check-spooky-season-once-an-hour: true
    inactive-goal-selector-disable: false
    reduce-entity-allocations: true
    cache-climb-check: true
    reduce-chuck-load-and-lookup: true
    cache-ignite-odds: true
    faster-chunk-serialization: true
    skip-secondary-POI-sensor-if-absent: true
    store-mob-counts-in-array: true
    optimize-noise-generation: false
    optimize-sun-burn-tick: true
    optimized-CubePointRange: true
    check-frozen-ticks-before-landing-block: true
    skip-entity-move-if-movement-is-zero: true
    skip-cloning-advancement-criteria: false
    skip-negligible-planar-movement-multiplication: true
    remove:
      tick-guard-lambda: true
      damage-lambda: true
  region:
    format: ANVIL
    linear:
      version: V2
      flush-delay-ms: 100
      use-virtual-thread: true
      flush-max-threads: 1
      compression-level: 1
```