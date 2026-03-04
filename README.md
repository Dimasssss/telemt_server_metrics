# Server Metrics 2026-03-04 10:05:24 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 46486.1 (12h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 662872
telemt_connections_bad_total 10946
telemt_handshake_timeouts_total 7427
telemt_upstream_connect_attempt_total 30860
telemt_upstream_connect_success_total 30732
telemt_upstream_connect_fail_total 54
telemt_upstream_connect_attempts_per_request{bucket="1"} 30732
telemt_upstream_connect_attempts_per_request{bucket="2"} 54
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17015
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13672
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 21
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 54
telemt_me_keepalive_timeout_total 332
telemt_me_reconnect_attempts_total 7045
telemt_me_reconnect_success_total 7001
telemt_me_reader_eof_total 7220
telemt_me_idle_close_by_peer_total 7220
telemt_me_route_drop_no_conn_total 236102
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_single_endpoint_shadow_rotate_total 185
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1144
telemt_desync_full_logged_total 397
telemt_desync_suppressed_total 747
telemt_desync_frames_bucket_total{bucket="1_2"} 315
telemt_desync_frames_bucket_total{bucket="3_10"} 436
telemt_desync_frames_bucket_total{bucket="gt_10"} 393
telemt_pool_swap_total 10
telemt_pool_force_close_total 430
telemt_me_writer_removed_unexpected_total 7220
telemt_me_writer_restored_same_endpoint_total 6980
telemt_me_writer_removed_unexpected_minus_restored_total 240
telemt_user_connections_total{user="hello"} 545645
telemt_user_connections_current{user="hello"} 1042
telemt_user_octets_from_client{user="hello"} 6143736664 (5.72 GB)
telemt_user_octets_to_client{user="hello"} 161075355868 (150.01 GB)
telemt_user_unique_ips_current{user="hello"} 121
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 46482.6 (12h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 267530
telemt_connections_bad_total 2387
telemt_handshake_timeouts_total 26231
telemt_upstream_connect_attempt_total 93856
telemt_upstream_connect_success_total 92511
telemt_upstream_connect_fail_total 634
telemt_upstream_connect_attempts_per_request{bucket="1"} 92505
telemt_upstream_connect_attempts_per_request{bucket="2"} 640
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 62131
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30358
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 634
telemt_me_keepalive_timeout_total 1344
telemt_me_reconnect_attempts_total 54316
telemt_me_reconnect_success_total 54234
telemt_me_reader_eof_total 55632
telemt_me_idle_close_by_peer_total 55631
telemt_me_route_drop_no_conn_total 122126
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 196
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 542
telemt_desync_full_logged_total 195
telemt_desync_suppressed_total 347
telemt_desync_frames_bucket_total{bucket="1_2"} 106
telemt_desync_frames_bucket_total{bucket="3_10"} 243
telemt_desync_frames_bucket_total{bucket="gt_10"} 193
telemt_pool_swap_total 3
telemt_pool_force_close_total 216
telemt_pool_stale_pick_total 56
telemt_me_writer_removed_unexpected_total 55712
telemt_me_writer_restored_same_endpoint_total 54209
telemt_me_writer_removed_unexpected_minus_restored_total 1503
telemt_user_connections_total{user="hello"} 205163
telemt_user_connections_current{user="hello"} 407
telemt_user_octets_from_client{user="hello"} 2533310832 (2.36 GB)
telemt_user_octets_to_client{user="hello"} 68037235872 (63.36 GB)
telemt_user_unique_ips_current{user="hello"} 40
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 46481.4 (12h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 535506
telemt_connections_bad_total 141810
telemt_handshake_timeouts_total 16208
telemt_upstream_connect_attempt_total 67185
telemt_upstream_connect_success_total 66765
telemt_upstream_connect_fail_total 200
telemt_upstream_connect_attempts_per_request{bucket="1"} 66764
telemt_upstream_connect_attempts_per_request{bucket="2"} 201
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38776
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27800
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 189
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 200
telemt_me_keepalive_timeout_total 882
telemt_me_reconnect_attempts_total 30458
telemt_me_reconnect_success_total 30376
telemt_me_reader_eof_total 32013
telemt_me_idle_close_by_peer_total 32010
telemt_me_route_drop_no_conn_total 182254
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_single_endpoint_shadow_rotate_total 196
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 874
telemt_desync_full_logged_total 319
telemt_desync_suppressed_total 555
telemt_desync_frames_bucket_total{bucket="1_2"} 257
telemt_desync_frames_bucket_total{bucket="3_10"} 301
telemt_desync_frames_bucket_total{bucket="gt_10"} 316
telemt_pool_swap_total 4
telemt_pool_force_close_total 201
telemt_me_writer_removed_unexpected_total 32024
telemt_me_writer_restored_same_endpoint_total 30355
telemt_me_writer_removed_unexpected_minus_restored_total 1669
telemt_user_connections_total{user="hello"} 360895
telemt_user_connections_current{user="hello"} 742
telemt_user_octets_from_client{user="hello"} 3888687564 (3.62 GB)
telemt_user_octets_to_client{user="hello"} 127620709108 (118.86 GB)
telemt_user_unique_ips_current{user="hello"} 71
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 46480.4 (12h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 344238
telemt_connections_bad_total 23965
telemt_handshake_timeouts_total 53513
telemt_upstream_connect_attempt_total 33365
telemt_upstream_connect_success_total 33226
telemt_upstream_connect_fail_total 68
telemt_upstream_connect_attempts_per_request{bucket="1"} 33226
telemt_upstream_connect_attempts_per_request{bucket="2"} 68
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20699
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12526
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 68
telemt_me_keepalive_timeout_total 379
telemt_me_reconnect_attempts_total 6666
telemt_me_reconnect_success_total 6644
telemt_me_reader_eof_total 6771
telemt_me_idle_close_by_peer_total 6771
telemt_me_route_drop_no_conn_total 97814
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_single_endpoint_shadow_rotate_total 191
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 179
telemt_desync_full_logged_total 77
telemt_desync_suppressed_total 102
telemt_desync_frames_bucket_total{bucket="1_2"} 46
telemt_desync_frames_bucket_total{bucket="3_10"} 85
telemt_desync_frames_bucket_total{bucket="gt_10"} 48
telemt_pool_swap_total 13
telemt_pool_force_close_total 315
telemt_me_writer_removed_unexpected_total 6771
telemt_me_writer_restored_same_endpoint_total 6623
telemt_me_writer_removed_unexpected_minus_restored_total 148
telemt_user_connections_total{user="hello"} 244626
telemt_user_connections_current{user="hello"} 444
telemt_user_octets_from_client{user="hello"} 2667133252 (2.48 GB)
telemt_user_octets_to_client{user="hello"} 85413501832 (79.55 GB)
telemt_user_unique_ips_current{user="hello"} 47
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 46479.1 (12h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 477089
telemt_connections_bad_total 6490
telemt_handshake_timeouts_total 132174
telemt_upstream_connect_attempt_total 68442
telemt_upstream_connect_success_total 67995
telemt_upstream_connect_fail_total 211
telemt_upstream_connect_attempts_per_request{bucket="1"} 67995
telemt_upstream_connect_attempts_per_request{bucket="2"} 211
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40815
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26992
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 186
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 211
telemt_me_keepalive_timeout_total 899
telemt_me_reconnect_attempts_total 33515
telemt_me_reconnect_success_total 33485
telemt_me_reader_eof_total 35163
telemt_me_idle_close_by_peer_total 35162
telemt_me_route_drop_no_conn_total 147410
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_single_endpoint_shadow_rotate_total 195
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 480
telemt_desync_full_logged_total 151
telemt_desync_suppressed_total 329
telemt_desync_frames_bucket_total{bucket="1_2"} 95
telemt_desync_frames_bucket_total{bucket="3_10"} 224
telemt_desync_frames_bucket_total{bucket="gt_10"} 161
telemt_pool_swap_total 6
telemt_pool_force_close_total 262
telemt_pool_stale_pick_total 2870
telemt_me_writer_removed_unexpected_total 35175
telemt_me_writer_restored_same_endpoint_total 33460
telemt_me_writer_removed_unexpected_minus_restored_total 1715
telemt_user_connections_total{user="hello"} 318229
telemt_user_connections_current{user="hello"} 545
telemt_user_octets_from_client{user="hello"} 4371795908 (4.07 GB)
telemt_user_octets_to_client{user="hello"} 79651609212 (74.18 GB)
telemt_user_connections_total{user="hello2"} 1
telemt_user_octets_from_client{user="hello2"} 140 (140 B)
telemt_user_octets_to_client{user="hello2"} 104 (104 B)
telemt_user_unique_ips_current{user="hello"} 48
```