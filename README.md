# Server Metrics 2026-03-04 14:36:58 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 62780.2 (17h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1155974
telemt_connections_bad_total 13992
telemt_handshake_timeouts_total 21329
telemt_upstream_connect_attempt_total 37330
telemt_upstream_connect_success_total 37163
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 37163
telemt_upstream_connect_attempts_per_request{bucket="2"} 65
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20454
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16634
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 42
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_timeout_total 429
telemt_me_reconnect_attempts_total 8172
telemt_me_reconnect_success_total 8112
telemt_me_reader_eof_total 8377
telemt_me_idle_close_by_peer_total 8376
telemt_me_route_drop_no_conn_total 427317
telemt_me_route_drop_channel_closed_total 3
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_single_endpoint_shadow_rotate_total 246
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 2137
telemt_desync_full_logged_total 704
telemt_desync_suppressed_total 1433
telemt_desync_frames_bucket_total{bucket="1_2"} 628
telemt_desync_frames_bucket_total{bucket="3_10"} 815
telemt_desync_frames_bucket_total{bucket="gt_10"} 694
telemt_pool_swap_total 16
telemt_pool_force_close_total 682
telemt_pool_stale_pick_total 76
telemt_me_writer_removed_unexpected_total 8377
telemt_me_writer_restored_same_endpoint_total 8090
telemt_me_writer_removed_unexpected_minus_restored_total 287
telemt_user_connections_total{user="hello"} 923697
telemt_user_connections_current{user="hello"} 1073
telemt_user_octets_from_client{user="hello"} 12318020476 (11.47 GB)
telemt_user_octets_to_client{user="hello"} 310196710828 (288.89 GB)
telemt_user_unique_ips_current{user="hello"} 113
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 62776.7 (17h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 439432
telemt_connections_bad_total 3750
telemt_handshake_timeouts_total 29628
telemt_upstream_connect_attempt_total 113111
telemt_upstream_connect_success_total 111435
telemt_upstream_connect_fail_total 800
telemt_upstream_connect_attempts_per_request{bucket="1"} 111429
telemt_upstream_connect_attempts_per_request{bucket="2"} 806
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 72824
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38587
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 800
telemt_me_keepalive_timeout_total 1505
telemt_me_reconnect_attempts_total 61883
telemt_me_reconnect_success_total 61785
telemt_me_reader_eof_total 63411
telemt_me_idle_close_by_peer_total 63410
telemt_me_route_drop_no_conn_total 178897
telemt_me_hardswap_pending_ttl_expired_total 19
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 263
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 975
telemt_desync_full_logged_total 290
telemt_desync_suppressed_total 685
telemt_desync_frames_bucket_total{bucket="1_2"} 189
telemt_desync_frames_bucket_total{bucket="3_10"} 408
telemt_desync_frames_bucket_total{bucket="gt_10"} 378
telemt_pool_swap_total 4
telemt_pool_force_close_total 281
telemt_pool_stale_pick_total 56
telemt_me_writer_removed_unexpected_total 63491
telemt_me_writer_restored_same_endpoint_total 61760
telemt_me_writer_removed_unexpected_minus_restored_total 1731
telemt_user_connections_total{user="hello"} 343418
telemt_user_connections_current{user="hello"} 472
telemt_user_octets_from_client{user="hello"} 4928382032 (4.59 GB)
telemt_user_octets_to_client{user="hello"} 109336398204 (101.83 GB)
telemt_user_unique_ips_current{user="hello"} 44
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 62775.5 (17h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 880186
telemt_connections_bad_total 186477
telemt_handshake_timeouts_total 29383
telemt_upstream_connect_attempt_total 84387
telemt_upstream_connect_success_total 83847
telemt_upstream_connect_fail_total 260
telemt_upstream_connect_attempts_per_request{bucket="1"} 83846
telemt_upstream_connect_attempts_per_request{bucket="2"} 261
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 49565
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34058
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 224
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 260
telemt_me_keepalive_timeout_total 1093
telemt_me_reconnect_attempts_total 38070
telemt_me_reconnect_success_total 37971
telemt_me_reader_eof_total 39969
telemt_me_idle_close_by_peer_total 39965
telemt_me_route_drop_no_conn_total 319920
telemt_me_hardswap_pending_ttl_expired_total 17
telemt_me_single_endpoint_shadow_rotate_total 259
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1836
telemt_desync_full_logged_total 608
telemt_desync_suppressed_total 1228
telemt_desync_frames_bucket_total{bucket="1_2"} 586
telemt_desync_frames_bucket_total{bucket="3_10"} 586
telemt_desync_frames_bucket_total{bucket="gt_10"} 664
telemt_pool_swap_total 7
telemt_pool_force_close_total 381
telemt_me_writer_removed_unexpected_total 39981
telemt_me_writer_restored_same_endpoint_total 37949
telemt_me_writer_removed_unexpected_minus_restored_total 2032
telemt_user_connections_total{user="hello"} 620959
telemt_user_connections_current{user="hello"} 685
telemt_user_octets_from_client{user="hello"} 12708524704 (11.84 GB)
telemt_user_octets_to_client{user="hello"} 212063355672 (197.50 GB)
telemt_user_unique_ips_current{user="hello"} 67
```

## server4

```
telemt 3.2.1

telemt_uptime_seconds 9452.9 (2h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 128723
telemt_connections_bad_total 12582
telemt_handshake_timeouts_total 4426
telemt_upstream_connect_attempt_total 4654
telemt_upstream_connect_success_total 4654
telemt_upstream_connect_attempts_per_request{bucket="1"} 4654
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2861
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1793
telemt_me_keepalive_timeout_total 52
telemt_me_reconnect_attempts_total 851
telemt_me_reconnect_success_total 863
telemt_me_reader_eof_total 870
telemt_me_idle_close_by_peer_total 870
telemt_me_route_drop_no_conn_total 45877
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 40
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 173
telemt_desync_full_logged_total 68
telemt_desync_suppressed_total 105
telemt_desync_frames_bucket_total{bucket="1_2"} 40
telemt_desync_frames_bucket_total{bucket="3_10"} 54
telemt_desync_frames_bucket_total{bucket="gt_10"} 79
telemt_pool_swap_total 3
telemt_pool_force_close_total 110
telemt_me_writer_removed_unexpected_total 870
telemt_me_writer_restored_same_endpoint_total 842
telemt_me_writer_removed_unexpected_minus_restored_total 28
telemt_user_connections_total{user="hello"} 108908
telemt_user_connections_current{user="hello"} 567
telemt_user_octets_from_client{user="hello"} 1623719908 (1.51 GB)
telemt_user_octets_to_client{user="hello"} 56913419596 (53.00 GB)
telemt_user_unique_ips_current{user="hello"} 62
```

## server5

```
telemt 3.2.1

telemt_uptime_seconds 9812.3 (2h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 168730
telemt_connections_bad_total 1856
telemt_handshake_timeouts_total 2736
telemt_upstream_connect_attempt_total 5622
telemt_upstream_connect_success_total 5593
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 5593
telemt_upstream_connect_attempts_per_request{bucket="2"} 14
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3253
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2331
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 82
telemt_me_reconnect_attempts_total 1218
telemt_me_reconnect_success_total 1227
telemt_me_reader_eof_total 1250
telemt_me_idle_close_by_peer_total 1250
telemt_me_route_drop_no_conn_total 60905
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 40
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 437
telemt_desync_full_logged_total 164
telemt_desync_suppressed_total 273
telemt_desync_frames_bucket_total{bucket="1_2"} 54
telemt_desync_frames_bucket_total{bucket="3_10"} 188
telemt_desync_frames_bucket_total{bucket="gt_10"} 195
telemt_pool_swap_total 2
telemt_pool_force_close_total 101
telemt_me_writer_removed_unexpected_total 1250
telemt_me_writer_restored_same_endpoint_total 1207
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 145598
telemt_user_connections_current{user="hello"} 527
telemt_user_octets_from_client{user="hello"} 1596848360 (1.49 GB)
telemt_user_octets_to_client{user="hello"} 40235933436 (37.47 GB)
telemt_user_unique_ips_current{user="hello"} 52
```