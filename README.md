# Server Metrics 2026-03-04 10:20:45 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 47407.5 (13h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 687672
telemt_connections_bad_total 10953
telemt_handshake_timeouts_total 7627
telemt_upstream_connect_attempt_total 30989
telemt_upstream_connect_success_total 30861
telemt_upstream_connect_fail_total 54
telemt_upstream_connect_attempts_per_request{bucket="1"} 30861
telemt_upstream_connect_attempts_per_request{bucket="2"} 54
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17065
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13751
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 21
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 54
telemt_me_keepalive_timeout_total 334
telemt_me_reconnect_attempts_total 7047
telemt_me_reconnect_success_total 7003
telemt_me_reader_eof_total 7222
telemt_me_idle_close_by_peer_total 7222
telemt_me_route_drop_no_conn_total 251820
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_single_endpoint_shadow_rotate_total 187
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1209
telemt_desync_full_logged_total 416
telemt_desync_suppressed_total 793
telemt_desync_frames_bucket_total{bucket="1_2"} 328
telemt_desync_frames_bucket_total{bucket="3_10"} 467
telemt_desync_frames_bucket_total{bucket="gt_10"} 414
telemt_pool_swap_total 11
telemt_pool_force_close_total 451
telemt_me_writer_removed_unexpected_total 7222
telemt_me_writer_restored_same_endpoint_total 6982
telemt_me_writer_removed_unexpected_minus_restored_total 240
telemt_user_connections_total{user="hello"} 568559
telemt_user_connections_current{user="hello"} 1013
telemt_user_octets_from_client{user="hello"} 6343389800 (5.91 GB)
telemt_user_octets_to_client{user="hello"} 173791495276 (161.86 GB)
telemt_user_unique_ips_current{user="hello"} 93
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 47404.0 (13h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 277389
telemt_connections_bad_total 2532
telemt_handshake_timeouts_total 26613
telemt_upstream_connect_attempt_total 94315
telemt_upstream_connect_success_total 92951
telemt_upstream_connect_fail_total 644
telemt_upstream_connect_attempts_per_request{bucket="1"} 92945
telemt_upstream_connect_attempts_per_request{bucket="2"} 650
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 62375
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30554
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 644
telemt_me_keepalive_timeout_total 1349
telemt_me_reconnect_attempts_total 54340
telemt_me_reconnect_success_total 54258
telemt_me_reader_eof_total 55656
telemt_me_idle_close_by_peer_total 55655
telemt_me_route_drop_no_conn_total 125138
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 200
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 552
telemt_desync_full_logged_total 198
telemt_desync_suppressed_total 354
telemt_desync_frames_bucket_total{bucket="1_2"} 108
telemt_desync_frames_bucket_total{bucket="3_10"} 247
telemt_desync_frames_bucket_total{bucket="gt_10"} 197
telemt_pool_swap_total 3
telemt_pool_force_close_total 216
telemt_pool_stale_pick_total 56
telemt_me_writer_removed_unexpected_total 55736
telemt_me_writer_restored_same_endpoint_total 54233
telemt_me_writer_removed_unexpected_minus_restored_total 1503
telemt_user_connections_total{user="hello"} 214168
telemt_user_connections_current{user="hello"} 466
telemt_user_octets_from_client{user="hello"} 2597958308 (2.42 GB)
telemt_user_octets_to_client{user="hello"} 70532292288 (65.69 GB)
telemt_user_unique_ips_current{user="hello"} 29
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 47402.8 (13h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 553854
telemt_connections_bad_total 144178
telemt_handshake_timeouts_total 16809
telemt_upstream_connect_attempt_total 69079
telemt_upstream_connect_success_total 68656
telemt_upstream_connect_fail_total 202
telemt_upstream_connect_attempts_per_request{bucket="1"} 68655
telemt_upstream_connect_attempts_per_request{bucket="2"} 203
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39972
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28490
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 194
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 202
telemt_me_keepalive_timeout_total 909
telemt_me_reconnect_attempts_total 31585
telemt_me_reconnect_success_total 31502
telemt_me_reader_eof_total 33210
telemt_me_idle_close_by_peer_total 33206
telemt_me_route_drop_no_conn_total 195674
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_single_endpoint_shadow_rotate_total 199
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 907
telemt_desync_full_logged_total 333
telemt_desync_suppressed_total 574
telemt_desync_frames_bucket_total{bucket="1_2"} 272
telemt_desync_frames_bucket_total{bucket="3_10"} 306
telemt_desync_frames_bucket_total{bucket="gt_10"} 329
telemt_pool_swap_total 4
telemt_pool_force_close_total 201
telemt_me_writer_removed_unexpected_total 33221
telemt_me_writer_restored_same_endpoint_total 31481
telemt_me_writer_removed_unexpected_minus_restored_total 1740
telemt_user_connections_total{user="hello"} 375398
telemt_user_connections_current{user="hello"} 613
telemt_user_octets_from_client{user="hello"} 4324284748 (4.03 GB)
telemt_user_octets_to_client{user="hello"} 131510217036 (122.48 GB)
telemt_user_unique_ips_current{user="hello"} 54
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 47402.0 (13h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 363070
telemt_connections_bad_total 24784
telemt_handshake_timeouts_total 61773
telemt_upstream_connect_attempt_total 34000
telemt_upstream_connect_success_total 33859
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 33859
telemt_upstream_connect_attempts_per_request{bucket="2"} 69
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21071
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12787
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_keepalive_timeout_total 382
telemt_me_reconnect_attempts_total 6787
telemt_me_reconnect_success_total 6763
telemt_me_reader_eof_total 6892
telemt_me_idle_close_by_peer_total 6892
telemt_me_route_drop_no_conn_total 101160
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_single_endpoint_shadow_rotate_total 195
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 201
telemt_desync_full_logged_total 82
telemt_desync_suppressed_total 119
telemt_desync_frames_bucket_total{bucket="1_2"} 48
telemt_desync_frames_bucket_total{bucket="3_10"} 93
telemt_desync_frames_bucket_total{bucket="gt_10"} 60
telemt_pool_swap_total 13
telemt_pool_force_close_total 315
telemt_me_writer_removed_unexpected_total 6892
telemt_me_writer_restored_same_endpoint_total 6742
telemt_me_writer_removed_unexpected_minus_restored_total 150
telemt_user_connections_total{user="hello"} 253679
telemt_user_connections_current{user="hello"} 346
telemt_user_octets_from_client{user="hello"} 2738109072 (2.55 GB)
telemt_user_octets_to_client{user="hello"} 90226571116 (84.03 GB)
telemt_user_unique_ips_current{user="hello"} 39
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 47400.6 (13h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 491356
telemt_connections_bad_total 6768
telemt_handshake_timeouts_total 132222
telemt_upstream_connect_attempt_total 68893
telemt_upstream_connect_success_total 68446
telemt_upstream_connect_fail_total 211
telemt_upstream_connect_attempts_per_request{bucket="1"} 68446
telemt_upstream_connect_attempts_per_request{bucket="2"} 211
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41096
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27160
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 188
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 211
telemt_me_keepalive_timeout_total 903
telemt_me_reconnect_attempts_total 33562
telemt_me_reconnect_success_total 33530
telemt_me_reader_eof_total 35209
telemt_me_idle_close_by_peer_total 35208
telemt_me_route_drop_no_conn_total 153094
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_single_endpoint_shadow_rotate_total 199
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 501
telemt_desync_full_logged_total 163
telemt_desync_suppressed_total 338
telemt_desync_frames_bucket_total{bucket="1_2"} 102
telemt_desync_frames_bucket_total{bucket="3_10"} 232
telemt_desync_frames_bucket_total{bucket="gt_10"} 167
telemt_pool_swap_total 6
telemt_pool_force_close_total 262
telemt_pool_stale_pick_total 2870
telemt_me_writer_removed_unexpected_total 35221
telemt_me_writer_restored_same_endpoint_total 33505
telemt_me_writer_removed_unexpected_minus_restored_total 1716
telemt_user_connections_total{user="hello"} 331799
telemt_user_connections_current{user="hello"} 524
telemt_user_octets_from_client{user="hello"} 4490682684 (4.18 GB)
telemt_user_octets_to_client{user="hello"} 83729450132 (77.98 GB)
telemt_user_connections_total{user="hello2"} 1
telemt_user_octets_from_client{user="hello2"} 140 (140 B)
telemt_user_octets_to_client{user="hello2"} 104 (104 B)
telemt_user_unique_ips_current{user="hello"} 52
```