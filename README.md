# Server Metrics 2026-03-06 17:38:40 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.4

telemt_uptime_seconds 26202.3 (7h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 777291
telemt_connections_bad_total 13386
telemt_handshake_timeouts_total 3340
telemt_upstream_connect_attempt_total 13222
telemt_upstream_connect_success_total 13140
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 13174
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7093
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5965
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 46
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_keepalive_timeout_total 174
telemt_me_reconnect_attempts_total 2664
telemt_me_reconnect_success_total 2644
telemt_me_reader_eof_total 2770
telemt_me_idle_close_by_peer_total 2770
telemt_me_route_drop_no_conn_total 326933
telemt_me_route_drop_channel_closed_total 3
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 103
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 3943
telemt_desync_full_logged_total 969
telemt_desync_suppressed_total 2974
telemt_desync_frames_bucket_total{bucket="1_2"} 925
telemt_desync_frames_bucket_total{bucket="3_10"} 1386
telemt_desync_frames_bucket_total{bucket="gt_10"} 1632
telemt_pool_swap_total 5
telemt_pool_force_close_total 313
telemt_me_writer_removed_unexpected_total 2773
telemt_me_writer_restored_same_endpoint_total 2638
telemt_me_writer_removed_unexpected_minus_restored_total 135
telemt_user_connections_total{user="hello"} 668100
telemt_user_connections_current{user="hello"} 1126
telemt_user_octets_from_client{user="hello"} 13884235252 (12.93 GB)
telemt_user_octets_to_client{user="hello"} 248790980780 (231.70 GB)
telemt_user_unique_ips_current{user="hello"} 296
telemt_user_unique_ips_recent_window{user="hello"} 159
```

## server2

```
telemt 3.3.4

telemt_uptime_seconds 26202.4 (7h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 288462
telemt_connections_bad_total 1137
telemt_handshake_timeouts_total 8315
telemt_upstream_connect_attempt_total 11723
telemt_upstream_connect_success_total 11690
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 11723
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5607
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6082
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_keepalive_timeout_total 153
telemt_me_reconnect_attempts_total 978
telemt_me_reconnect_success_total 954
telemt_me_reader_eof_total 1007
telemt_me_idle_close_by_peer_total 1007
telemt_me_route_drop_no_conn_total 155592
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 107
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 922
telemt_desync_full_logged_total 294
telemt_desync_suppressed_total 628
telemt_desync_frames_bucket_total{bucket="1_2"} 169
telemt_desync_frames_bucket_total{bucket="3_10"} 339
telemt_desync_frames_bucket_total{bucket="gt_10"} 414
telemt_pool_swap_total 7
telemt_pool_force_close_total 282
telemt_me_writer_removed_unexpected_total 1008
telemt_me_writer_restored_same_endpoint_total 954
telemt_me_writer_removed_unexpected_minus_restored_total 54
telemt_user_connections_total{user="hello"} 265767
telemt_user_connections_current{user="hello"} 448
telemt_user_octets_from_client{user="hello"} 3292049880 (3.07 GB)
telemt_user_octets_to_client{user="hello"} 106088831308 (98.80 GB)
telemt_user_unique_ips_current{user="hello"} 124
telemt_user_unique_ips_recent_window{user="hello"} 63
```

## server3

```
telemt 3.3.4

telemt_uptime_seconds 26202.3 (7h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 563000
telemt_connections_bad_total 5553
telemt_handshake_timeouts_total 52793
telemt_upstream_connect_attempt_total 22848
telemt_upstream_connect_success_total 22739
telemt_upstream_connect_fail_total 79
telemt_upstream_connect_attempts_per_request{bucket="1"} 22818
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12509
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10178
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 79
telemt_me_keepalive_timeout_total 341
telemt_me_reconnect_attempts_total 7966
telemt_me_reconnect_success_total 7935
telemt_me_reader_eof_total 8431
telemt_me_idle_close_by_peer_total 8431
telemt_me_route_drop_no_conn_total 297516
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 105
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 1440
telemt_desync_full_logged_total 419
telemt_desync_suppressed_total 1021
telemt_desync_frames_bucket_total{bucket="1_2"} 327
telemt_desync_frames_bucket_total{bucket="3_10"} 537
telemt_desync_frames_bucket_total{bucket="gt_10"} 576
telemt_pool_swap_total 3
telemt_pool_force_close_total 237
telemt_pool_stale_pick_total 381
telemt_me_writer_removed_unexpected_total 8446
telemt_me_writer_restored_same_endpoint_total 7928
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 516
telemt_user_connections_total{user="hello"} 485853
telemt_user_connections_current{user="hello"} 689
telemt_user_octets_from_client{user="hello"} 7252959316 (6.75 GB)
telemt_user_octets_to_client{user="hello"} 150252737224 (139.93 GB)
telemt_user_unique_ips_current{user="hello"} 184
telemt_user_unique_ips_recent_window{user="hello"} 93
```

## server4

```
telemt 3.3.4

telemt_uptime_seconds 25518.2 (7h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 549564
telemt_connections_bad_total 188945
telemt_handshake_timeouts_total 14022
telemt_upstream_connect_attempt_total 17868
telemt_upstream_connect_success_total 17866
telemt_upstream_connect_attempts_per_request{bucket="1"} 17866
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10072
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7794
telemt_me_keepalive_timeout_total 257
telemt_me_reconnect_attempts_total 5138
telemt_me_reconnect_success_total 5113
telemt_me_reader_eof_total 5354
telemt_me_idle_close_by_peer_total 5354
telemt_me_route_drop_no_conn_total 177651
telemt_me_route_drop_channel_closed_total 2
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 109
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 1
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_desync_total 369
telemt_desync_full_logged_total 143
telemt_desync_suppressed_total 226
telemt_desync_frames_bucket_total{bucket="1_2"} 98
telemt_desync_frames_bucket_total{bucket="3_10"} 124
telemt_desync_frames_bucket_total{bucket="gt_10"} 147
telemt_pool_swap_total 5
telemt_pool_force_close_total 269
telemt_me_writer_removed_unexpected_total 5360
telemt_me_writer_restored_same_endpoint_total 5112
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 247
telemt_user_connections_total{user="hello"} 308893
telemt_user_connections_current{user="hello"} 556
telemt_user_octets_from_client{user="hello"} 5079631780 (4.73 GB)
telemt_user_octets_to_client{user="hello"} 108923202792 (101.44 GB)
telemt_user_unique_ips_current{user="hello"} 132
telemt_user_unique_ips_recent_window{user="hello"} 71
```

## server5

```
telemt 3.3.4

telemt_uptime_seconds 26202.6 (7h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 486980
telemt_connections_bad_total 11141
telemt_handshake_timeouts_total 5074
telemt_upstream_connect_attempt_total 11026
telemt_upstream_connect_success_total 11009
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 11010
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5928
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5014
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 65
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 182
telemt_me_reconnect_attempts_total 1791
telemt_me_reconnect_success_total 1771
telemt_me_reader_eof_total 1871
telemt_me_idle_close_by_peer_total 1870
telemt_me_route_drop_no_conn_total 227005
telemt_me_route_drop_channel_closed_total 6
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 102
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 915
telemt_desync_full_logged_total 329
telemt_desync_suppressed_total 586
telemt_desync_frames_bucket_total{bucket="1_2"} 406
telemt_desync_frames_bucket_total{bucket="3_10"} 268
telemt_desync_frames_bucket_total{bucket="gt_10"} 241
telemt_pool_swap_total 8
telemt_pool_force_close_total 297
telemt_pool_stale_pick_total 293
telemt_me_writer_removed_unexpected_total 1875
telemt_me_writer_restored_same_endpoint_total 1768
telemt_me_writer_removed_unexpected_minus_restored_total 107
telemt_user_connections_total{user="hello"} 446515
telemt_user_connections_current{user="hello"} 525
telemt_user_octets_from_client{user="hello"} 20768009592 (19.34 GB)
telemt_user_octets_to_client{user="hello"} 212066258176 (197.50 GB)
telemt_user_unique_ips_current{user="hello"} 141
telemt_user_unique_ips_recent_window{user="hello"} 72
```