# Server Metrics 2026-03-04 05:59:09 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 31711.1 (8h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 250914
telemt_connections_bad_total 2435
telemt_handshake_timeouts_total 4869
telemt_upstream_connect_attempt_total 21360
telemt_upstream_connect_success_total 21261
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 21261
telemt_upstream_connect_attempts_per_request{bucket="2"} 44
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12091
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9140
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 12
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_keepalive_timeout_total 222
telemt_me_reconnect_attempts_total 4612
telemt_me_reconnect_success_total 4590
telemt_me_reader_eof_total 4696
telemt_me_idle_close_by_peer_total 4696
telemt_me_route_drop_no_conn_total 90975
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 130
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 658
telemt_desync_full_logged_total 249
telemt_desync_suppressed_total 409
telemt_desync_frames_bucket_total{bucket="1_2"} 190
telemt_desync_frames_bucket_total{bucket="3_10"} 231
telemt_desync_frames_bucket_total{bucket="gt_10"} 237
telemt_pool_swap_total 7
telemt_pool_force_close_total 253
telemt_me_writer_removed_unexpected_total 4696
telemt_me_writer_restored_same_endpoint_total 4570
telemt_me_writer_removed_unexpected_minus_restored_total 126
telemt_user_connections_total{user="hello"} 237085
telemt_user_connections_current{user="hello"} 774
telemt_user_octets_from_client{user="hello"} 2508962476 (2.34 GB)
telemt_user_octets_to_client{user="hello"} 76767727664 (71.50 GB)
telemt_user_unique_ips_current{user="hello"} 86
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 31707.5 (8h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 128464
telemt_connections_bad_total 410
telemt_handshake_timeouts_total 22028
telemt_upstream_connect_attempt_total 71163
telemt_upstream_connect_success_total 70306
telemt_upstream_connect_fail_total 412
telemt_upstream_connect_attempts_per_request{bucket="1"} 70300
telemt_upstream_connect_attempts_per_request{bucket="2"} 418
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 47481
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22805
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 412
telemt_me_keepalive_timeout_total 1031
telemt_me_reconnect_attempts_total 42616
telemt_me_reconnect_success_total 42587
telemt_me_reader_eof_total 43655
telemt_me_idle_close_by_peer_total 43654
telemt_me_route_drop_no_conn_total 37914
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_single_endpoint_shadow_rotate_total 138
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 255
telemt_desync_full_logged_total 96
telemt_desync_suppressed_total 159
telemt_desync_frames_bucket_total{bucket="1_2"} 60
telemt_desync_frames_bucket_total{bucket="3_10"} 138
telemt_desync_frames_bucket_total{bucket="gt_10"} 57
telemt_pool_swap_total 1
telemt_pool_force_close_total 75
telemt_me_writer_removed_unexpected_total 43716
telemt_me_writer_restored_same_endpoint_total 42566
telemt_me_writer_removed_unexpected_minus_restored_total 1150
telemt_user_connections_total{user="hello"} 85917
telemt_user_connections_current{user="hello"} 326
telemt_user_octets_from_client{user="hello"} 767280748 (731.74 MB)
telemt_user_octets_to_client{user="hello"} 35833839008 (33.37 GB)
telemt_user_unique_ips_current{user="hello"} 35
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 31706.3 (8h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 259091
telemt_connections_bad_total 90746
telemt_handshake_timeouts_total 5336
telemt_upstream_connect_attempt_total 42679
telemt_upstream_connect_success_total 42408
telemt_upstream_connect_fail_total 127
telemt_upstream_connect_attempts_per_request{bucket="1"} 42408
telemt_upstream_connect_attempts_per_request{bucket="2"} 127
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24641
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17644
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 123
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 127
telemt_me_keepalive_timeout_total 553
telemt_me_reconnect_attempts_total 17447
telemt_me_reconnect_success_total 17400
telemt_me_reader_eof_total 18339
telemt_me_idle_close_by_peer_total 18336
telemt_me_route_drop_no_conn_total 55855
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_single_endpoint_shadow_rotate_total 137
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 380
telemt_desync_full_logged_total 140
telemt_desync_suppressed_total 240
telemt_desync_frames_bucket_total{bucket="1_2"} 98
telemt_desync_frames_bucket_total{bucket="3_10"} 143
telemt_desync_frames_bucket_total{bucket="gt_10"} 139
telemt_pool_swap_total 3
telemt_pool_force_close_total 113
telemt_me_writer_removed_unexpected_total 18347
telemt_me_writer_restored_same_endpoint_total 17379
telemt_me_writer_removed_unexpected_minus_restored_total 968
telemt_user_connections_total{user="hello"} 155349
telemt_user_connections_current{user="hello"} 518
telemt_user_octets_from_client{user="hello"} 1118924300 (1.04 GB)
telemt_user_octets_to_client{user="hello"} 40505033960 (37.72 GB)
telemt_user_unique_ips_current{user="hello"} 67
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 31705.3 (8h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 133554
telemt_connections_bad_total 10532
telemt_handshake_timeouts_total 2626
telemt_upstream_connect_attempt_total 24501
telemt_upstream_connect_success_total 24409
telemt_upstream_connect_fail_total 45
telemt_upstream_connect_attempts_per_request{bucket="1"} 24409
telemt_upstream_connect_attempts_per_request{bucket="2"} 45
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15197
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9211
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 45
telemt_me_keepalive_timeout_total 256
telemt_me_reconnect_attempts_total 5166
telemt_me_reconnect_success_total 5157
telemt_me_reader_eof_total 5248
telemt_me_idle_close_by_peer_total 5248
telemt_me_route_drop_no_conn_total 40238
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 135
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 141
telemt_desync_full_logged_total 61
telemt_desync_suppressed_total 80
telemt_desync_frames_bucket_total{bucket="1_2"} 31
telemt_desync_frames_bucket_total{bucket="3_10"} 75
telemt_desync_frames_bucket_total{bucket="gt_10"} 35
telemt_pool_swap_total 8
telemt_pool_force_close_total 184
telemt_me_writer_removed_unexpected_total 5248
telemt_me_writer_restored_same_endpoint_total 5136
telemt_me_writer_removed_unexpected_minus_restored_total 112
telemt_user_connections_total{user="hello"} 113972
telemt_user_connections_current{user="hello"} 218
telemt_user_octets_from_client{user="hello"} 994599844 (948.52 MB)
telemt_user_octets_to_client{user="hello"} 42840276440 (39.90 GB)
telemt_user_unique_ips_current{user="hello"} 29
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 31704.0 (8h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 275935
telemt_connections_bad_total 5438
telemt_handshake_timeouts_total 125397
telemt_upstream_connect_attempt_total 45292
telemt_upstream_connect_success_total 44972
telemt_upstream_connect_fail_total 150
telemt_upstream_connect_attempts_per_request{bucket="1"} 44972
telemt_upstream_connect_attempts_per_request{bucket="2"} 150
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26733
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18126
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 111
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 150
telemt_me_keepalive_timeout_total 620
telemt_me_reconnect_attempts_total 21466
telemt_me_reconnect_success_total 21455
telemt_me_reader_eof_total 22639
telemt_me_idle_close_by_peer_total 22638
telemt_me_route_drop_no_conn_total 61176
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_single_endpoint_shadow_rotate_total 135
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 202
telemt_desync_full_logged_total 65
telemt_desync_suppressed_total 137
telemt_desync_frames_bucket_total{bucket="1_2"} 32
telemt_desync_frames_bucket_total{bucket="3_10"} 107
telemt_desync_frames_bucket_total{bucket="gt_10"} 63
telemt_pool_swap_total 4
telemt_pool_force_close_total 114
telemt_pool_stale_pick_total 2751
telemt_me_writer_removed_unexpected_total 22652
telemt_me_writer_restored_same_endpoint_total 21430
telemt_me_writer_removed_unexpected_minus_restored_total 1222
telemt_user_connections_total{user="hello"} 140376
telemt_user_connections_current{user="hello"} 389
telemt_user_octets_from_client{user="hello"} 1993193544 (1.86 GB)
telemt_user_octets_to_client{user="hello"} 32529225028 (30.30 GB)
telemt_user_unique_ips_current{user="hello"} 52
```