# Server Metrics 2026-03-04 14:11:21 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 61243.2 (17h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1116293
telemt_connections_bad_total 13921
telemt_handshake_timeouts_total 19883
telemt_upstream_connect_attempt_total 36932
telemt_upstream_connect_success_total 36765
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 36765
telemt_upstream_connect_attempts_per_request{bucket="2"} 65
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20234
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16456
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 42
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_timeout_total 420
telemt_me_reconnect_attempts_total 8144
telemt_me_reconnect_success_total 8085
telemt_me_reader_eof_total 8349
telemt_me_idle_close_by_peer_total 8348
telemt_me_route_drop_no_conn_total 414016
telemt_me_route_drop_channel_closed_total 3
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_single_endpoint_shadow_rotate_total 240
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1949
telemt_desync_full_logged_total 648
telemt_desync_suppressed_total 1301
telemt_desync_frames_bucket_total{bucket="1_2"} 566
telemt_desync_frames_bucket_total{bucket="3_10"} 738
telemt_desync_frames_bucket_total{bucket="gt_10"} 645
telemt_pool_swap_total 15
telemt_pool_force_close_total 576
telemt_pool_stale_pick_total 76
telemt_me_writer_removed_unexpected_total 8349
telemt_me_writer_restored_same_endpoint_total 8063
telemt_me_writer_removed_unexpected_minus_restored_total 286
telemt_user_connections_total{user="hello"} 887314
telemt_user_connections_current{user="hello"} 1112
telemt_user_octets_from_client{user="hello"} 11072621132 (10.31 GB)
telemt_user_octets_to_client{user="hello"} 299006750588 (278.47 GB)
telemt_user_unique_ips_current{user="hello"} 95
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 61239.7 (17h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 427192
telemt_connections_bad_total 3632
telemt_handshake_timeouts_total 29507
telemt_upstream_connect_attempt_total 110013
telemt_upstream_connect_success_total 108359
telemt_upstream_connect_fail_total 789
telemt_upstream_connect_attempts_per_request{bucket="1"} 108353
telemt_upstream_connect_attempts_per_request{bucket="2"} 795
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 71097
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 789
telemt_me_keepalive_timeout_total 1484
telemt_me_reconnect_attempts_total 60305
telemt_me_reconnect_success_total 60209
telemt_me_reader_eof_total 61800
telemt_me_idle_close_by_peer_total 61799
telemt_me_route_drop_no_conn_total 174000
telemt_me_hardswap_pending_ttl_expired_total 18
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 256
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 857
telemt_desync_full_logged_total 264
telemt_desync_suppressed_total 593
telemt_desync_frames_bucket_total{bucket="1_2"} 165
telemt_desync_frames_bucket_total{bucket="3_10"} 352
telemt_desync_frames_bucket_total{bucket="gt_10"} 340
telemt_pool_swap_total 4
telemt_pool_force_close_total 281
telemt_pool_stale_pick_total 56
telemt_me_writer_removed_unexpected_total 61880
telemt_me_writer_restored_same_endpoint_total 60184
telemt_me_writer_removed_unexpected_minus_restored_total 1696
telemt_user_connections_total{user="hello"} 331768
telemt_user_connections_current{user="hello"} 400
telemt_user_octets_from_client{user="hello"} 4233796776 (3.94 GB)
telemt_user_octets_to_client{user="hello"} 105258686840 (98.03 GB)
telemt_user_unique_ips_current{user="hello"} 50
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 61238.5 (17h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 843551
telemt_connections_bad_total 182152
telemt_handshake_timeouts_total 29216
telemt_upstream_connect_attempt_total 83513
telemt_upstream_connect_success_total 82992
telemt_upstream_connect_fail_total 251
telemt_upstream_connect_attempts_per_request{bucket="1"} 82991
telemt_upstream_connect_attempts_per_request{bucket="2"} 252
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 49022
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33748
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 222
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 251
telemt_me_keepalive_timeout_total 1090
telemt_me_reconnect_attempts_total 37956
telemt_me_reconnect_success_total 37857
telemt_me_reader_eof_total 39851
telemt_me_idle_close_by_peer_total 39847
telemt_me_route_drop_no_conn_total 307821
telemt_me_hardswap_pending_ttl_expired_total 17
telemt_me_single_endpoint_shadow_rotate_total 252
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1726
telemt_desync_full_logged_total 581
telemt_desync_suppressed_total 1145
telemt_desync_frames_bucket_total{bucket="1_2"} 563
telemt_desync_frames_bucket_total{bucket="3_10"} 552
telemt_desync_frames_bucket_total{bucket="gt_10"} 611
telemt_pool_swap_total 7
telemt_pool_force_close_total 381
telemt_me_writer_removed_unexpected_total 39863
telemt_me_writer_restored_same_endpoint_total 37835
telemt_me_writer_removed_unexpected_minus_restored_total 2028
telemt_user_connections_total{user="hello"} 594191
telemt_user_connections_current{user="hello"} 800
telemt_user_octets_from_client{user="hello"} 12461969840 (11.61 GB)
telemt_user_octets_to_client{user="hello"} 201923097416 (188.06 GB)
telemt_user_unique_ips_current{user="hello"} 94
```

## server4

```
telemt 3.2.1

telemt_uptime_seconds 7915.9 (2h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 100675
telemt_connections_bad_total 10544
telemt_handshake_timeouts_total 2343
telemt_upstream_connect_attempt_total 4136
telemt_upstream_connect_success_total 4136
telemt_upstream_connect_attempts_per_request{bucket="1"} 4136
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2549
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1587
telemt_me_keepalive_timeout_total 42
telemt_me_reconnect_attempts_total 735
telemt_me_reconnect_success_total 749
telemt_me_reader_eof_total 747
telemt_me_idle_close_by_peer_total 747
telemt_me_route_drop_no_conn_total 37542
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 34
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 149
telemt_desync_full_logged_total 61
telemt_desync_suppressed_total 88
telemt_desync_frames_bucket_total{bucket="1_2"} 37
telemt_desync_frames_bucket_total{bucket="3_10"} 44
telemt_desync_frames_bucket_total{bucket="gt_10"} 68
telemt_pool_swap_total 1
telemt_pool_force_close_total 41
telemt_me_writer_removed_unexpected_total 747
telemt_me_writer_restored_same_endpoint_total 728
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 86138
telemt_user_connections_current{user="hello"} 548
telemt_user_octets_from_client{user="hello"} 1405578108 (1.31 GB)
telemt_user_octets_to_client{user="hello"} 51252756288 (47.73 GB)
telemt_user_unique_ips_current{user="hello"} 66
```

## server5

```
telemt 3.2.1

telemt_uptime_seconds 8275.1 (2h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 143884
telemt_connections_bad_total 924
telemt_handshake_timeouts_total 2461
telemt_upstream_connect_attempt_total 5131
telemt_upstream_connect_success_total 5104
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 5104
telemt_upstream_connect_attempts_per_request{bucket="2"} 13
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3004
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2091
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 72
telemt_me_reconnect_attempts_total 1206
telemt_me_reconnect_success_total 1216
telemt_me_reader_eof_total 1239
telemt_me_idle_close_by_peer_total 1239
telemt_me_route_drop_no_conn_total 50157
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 37
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 391
telemt_desync_full_logged_total 145
telemt_desync_suppressed_total 246
telemt_desync_frames_bucket_total{bucket="1_2"} 50
telemt_desync_frames_bucket_total{bucket="3_10"} 163
telemt_desync_frames_bucket_total{bucket="gt_10"} 178
telemt_pool_swap_total 1
telemt_pool_force_close_total 53
telemt_me_writer_removed_unexpected_total 1239
telemt_me_writer_restored_same_endpoint_total 1196
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 123750
telemt_user_connections_current{user="hello"} 653
telemt_user_octets_from_client{user="hello"} 1435097612 (1.34 GB)
telemt_user_octets_to_client{user="hello"} 35003636464 (32.60 GB)
telemt_user_unique_ips_current{user="hello"} 69
```