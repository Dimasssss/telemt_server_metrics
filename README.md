# Server Metrics 2026-03-06 16:16:24 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.4

telemt_uptime_seconds 21266.8 (5h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 641746
telemt_connections_bad_total 9127
telemt_handshake_timeouts_total 3018
telemt_upstream_connect_attempt_total 10346
telemt_upstream_connect_success_total 10282
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 10309
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5445
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4774
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 39
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_keepalive_timeout_total 135
telemt_me_reconnect_attempts_total 1990
telemt_me_reconnect_success_total 1976
telemt_me_reader_eof_total 2076
telemt_me_idle_close_by_peer_total 2076
telemt_me_route_drop_no_conn_total 270242
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 85
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 3303
telemt_desync_full_logged_total 795
telemt_desync_suppressed_total 2508
telemt_desync_frames_bucket_total{bucket="1_2"} 782
telemt_desync_frames_bucket_total{bucket="3_10"} 1134
telemt_desync_frames_bucket_total{bucket="gt_10"} 1387
telemt_pool_swap_total 4
telemt_pool_force_close_total 234
telemt_me_writer_removed_unexpected_total 2078
telemt_me_writer_restored_same_endpoint_total 1970
telemt_me_writer_removed_unexpected_minus_restored_total 108
telemt_user_connections_total{user="hello"} 551365
telemt_user_connections_current{user="hello"} 1143
telemt_user_octets_from_client{user="hello"} 12623844504 (11.76 GB)
telemt_user_octets_to_client{user="hello"} 206565384152 (192.38 GB)
telemt_user_unique_ips_current{user="hello"} 305
telemt_user_unique_ips_recent_window{user="hello"} 158
```

## server2

```
telemt 3.3.4

telemt_uptime_seconds 21266.5 (5h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 240509
telemt_connections_bad_total 867
telemt_handshake_timeouts_total 6904
telemt_upstream_connect_attempt_total 10073
telemt_upstream_connect_success_total 10049
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 10072
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4848
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5200
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_timeout_total 127
telemt_me_reconnect_attempts_total 942
telemt_me_reconnect_success_total 924
telemt_me_reader_eof_total 975
telemt_me_idle_close_by_peer_total 975
telemt_me_route_drop_no_conn_total 135964
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 88
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 801
telemt_desync_full_logged_total 262
telemt_desync_suppressed_total 539
telemt_desync_frames_bucket_total{bucket="1_2"} 143
telemt_desync_frames_bucket_total{bucket="3_10"} 297
telemt_desync_frames_bucket_total{bucket="gt_10"} 361
telemt_pool_swap_total 5
telemt_pool_force_close_total 196
telemt_me_writer_removed_unexpected_total 976
telemt_me_writer_restored_same_endpoint_total 924
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 222055
telemt_user_connections_current{user="hello"} 478
telemt_user_octets_from_client{user="hello"} 2575944684 (2.40 GB)
telemt_user_octets_to_client{user="hello"} 89575535616 (83.42 GB)
telemt_user_unique_ips_current{user="hello"} 144
telemt_user_unique_ips_recent_window{user="hello"} 70
```

## server3

```
telemt 3.3.4

telemt_uptime_seconds 21266.5 (5h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 483825
telemt_connections_bad_total 5420
telemt_handshake_timeouts_total 49946
telemt_upstream_connect_attempt_total 17322
telemt_upstream_connect_success_total 17243
telemt_upstream_connect_fail_total 67
telemt_upstream_connect_attempts_per_request{bucket="1"} 17310
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9594
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7617
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 67
telemt_me_keepalive_timeout_total 230
telemt_me_reconnect_attempts_total 5708
telemt_me_reconnect_success_total 5684
telemt_me_reader_eof_total 6003
telemt_me_idle_close_by_peer_total 6003
telemt_me_route_drop_no_conn_total 242491
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 86
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 1020
telemt_desync_full_logged_total 303
telemt_desync_suppressed_total 717
telemt_desync_frames_bucket_total{bucket="1_2"} 240
telemt_desync_frames_bucket_total{bucket="3_10"} 391
telemt_desync_frames_bucket_total{bucket="gt_10"} 389
telemt_pool_swap_total 2
telemt_pool_force_close_total 169
telemt_pool_stale_pick_total 381
telemt_me_writer_removed_unexpected_total 6015
telemt_me_writer_restored_same_endpoint_total 5677
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 336
telemt_user_connections_total{user="hello"} 413425
telemt_user_connections_current{user="hello"} 737
telemt_user_octets_from_client{user="hello"} 6068191972 (5.65 GB)
telemt_user_octets_to_client{user="hello"} 129945778892 (121.02 GB)
telemt_user_unique_ips_current{user="hello"} 192
telemt_user_unique_ips_recent_window{user="hello"} 123
```

## server4

```
telemt 3.3.4

telemt_uptime_seconds 20582.5 (5h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 422754
telemt_connections_bad_total 131615
telemt_handshake_timeouts_total 10882
telemt_upstream_connect_attempt_total 11166
telemt_upstream_connect_success_total 11165
telemt_upstream_connect_attempts_per_request{bucket="1"} 11165
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6657
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4508
telemt_me_keepalive_timeout_total 133
telemt_me_reconnect_attempts_total 2165
telemt_me_reconnect_success_total 2148
telemt_me_reader_eof_total 2190
telemt_me_idle_close_by_peer_total 2190
telemt_me_route_drop_no_conn_total 132675
telemt_me_route_drop_channel_closed_total 2
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 87
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 1
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_desync_total 340
telemt_desync_full_logged_total 126
telemt_desync_suppressed_total 214
telemt_desync_frames_bucket_total{bucket="1_2"} 85
telemt_desync_frames_bucket_total{bucket="3_10"} 115
telemt_desync_frames_bucket_total{bucket="gt_10"} 140
telemt_pool_swap_total 4
telemt_pool_force_close_total 192
telemt_me_writer_removed_unexpected_total 2196
telemt_me_writer_restored_same_endpoint_total 2147
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 48
telemt_user_connections_total{user="hello"} 244597
telemt_user_connections_current{user="hello"} 590
telemt_user_octets_from_client{user="hello"} 4349414140 (4.05 GB)
telemt_user_octets_to_client{user="hello"} 88554586044 (82.47 GB)
telemt_user_unique_ips_current{user="hello"} 138
telemt_user_unique_ips_recent_window{user="hello"} 89
```

## server5

```
telemt 3.3.4

telemt_uptime_seconds 21266.7 (5h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 378634
telemt_connections_bad_total 11044
telemt_handshake_timeouts_total 3109
telemt_upstream_connect_attempt_total 9677
telemt_upstream_connect_success_total 9665
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 9666
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5258
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4347
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 159
telemt_me_reconnect_attempts_total 1766
telemt_me_reconnect_success_total 1750
telemt_me_reader_eof_total 1845
telemt_me_idle_close_by_peer_total 1844
telemt_me_route_drop_no_conn_total 188921
telemt_me_route_drop_channel_closed_total 4
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 82
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 702
telemt_desync_full_logged_total 244
telemt_desync_suppressed_total 458
telemt_desync_frames_bucket_total{bucket="1_2"} 321
telemt_desync_frames_bucket_total{bucket="3_10"} 208
telemt_desync_frames_bucket_total{bucket="gt_10"} 173
telemt_pool_swap_total 7
telemt_pool_force_close_total 255
telemt_pool_stale_pick_total 160
telemt_me_writer_removed_unexpected_total 1849
telemt_me_writer_restored_same_endpoint_total 1747
telemt_me_writer_removed_unexpected_minus_restored_total 102
telemt_user_connections_total{user="hello"} 347485
telemt_user_connections_current{user="hello"} 525
telemt_user_octets_from_client{user="hello"} 15202654132 (14.16 GB)
telemt_user_octets_to_client{user="hello"} 180133287132 (167.76 GB)
telemt_user_unique_ips_current{user="hello"} 149
telemt_user_unique_ips_recent_window{user="hello"} 103
```