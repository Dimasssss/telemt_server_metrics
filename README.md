# Server Metrics 2026-03-04 11:37:34 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 52016.6 (14h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 841585
telemt_connections_bad_total 12051
telemt_handshake_timeouts_total 11591
telemt_upstream_connect_attempt_total 32367
telemt_upstream_connect_success_total 32230
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 32230
telemt_upstream_connect_attempts_per_request{bucket="2"} 58
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17821
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14360
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_keepalive_timeout_total 360
telemt_me_reconnect_attempts_total 7082
telemt_me_reconnect_success_total 7036
telemt_me_reader_eof_total 7255
telemt_me_idle_close_by_peer_total 7255
telemt_me_route_drop_no_conn_total 321216
telemt_me_route_drop_channel_closed_total 3
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_single_endpoint_shadow_rotate_total 203
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1374
telemt_desync_full_logged_total 466
telemt_desync_suppressed_total 908
telemt_desync_frames_bucket_total{bucket="1_2"} 385
telemt_desync_frames_bucket_total{bucket="3_10"} 535
telemt_desync_frames_bucket_total{bucket="gt_10"} 454
telemt_pool_swap_total 13
telemt_pool_force_close_total 524
telemt_pool_stale_pick_total 76
telemt_me_writer_removed_unexpected_total 7255
telemt_me_writer_restored_same_endpoint_total 7015
telemt_me_writer_removed_unexpected_minus_restored_total 240
telemt_user_connections_total{user="hello"} 677921
telemt_user_connections_current{user="hello"} 1061
telemt_user_octets_from_client{user="hello"} 7376007932 (6.87 GB)
telemt_user_octets_to_client{user="hello"} 206078917540 (191.93 GB)
telemt_user_unique_ips_current{user="hello"} 105
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 52013.1 (14h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 335899
telemt_connections_bad_total 2926
telemt_handshake_timeouts_total 27328
telemt_upstream_connect_attempt_total 100226
telemt_upstream_connect_success_total 98704
telemt_upstream_connect_fail_total 723
telemt_upstream_connect_attempts_per_request{bucket="1"} 98698
telemt_upstream_connect_attempts_per_request{bucket="2"} 729
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 66084
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32596
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 723
telemt_me_keepalive_timeout_total 1389
telemt_me_reconnect_attempts_total 56605
telemt_me_reconnect_success_total 56518
telemt_me_reader_eof_total 57949
telemt_me_idle_close_by_peer_total 57948
telemt_me_route_drop_no_conn_total 141727
telemt_me_hardswap_pending_ttl_expired_total 16
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 220
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 621
telemt_desync_full_logged_total 216
telemt_desync_suppressed_total 405
telemt_desync_frames_bucket_total{bucket="1_2"} 127
telemt_desync_frames_bucket_total{bucket="3_10"} 270
telemt_desync_frames_bucket_total{bucket="gt_10"} 224
telemt_pool_swap_total 3
telemt_pool_force_close_total 216
telemt_pool_stale_pick_total 56
telemt_me_writer_removed_unexpected_total 58029
telemt_me_writer_restored_same_endpoint_total 56493
telemt_me_writer_removed_unexpected_minus_restored_total 1536
telemt_user_connections_total{user="hello"} 253659
telemt_user_connections_current{user="hello"} 402
telemt_user_octets_from_client{user="hello"} 3314940380 (3.09 GB)
telemt_user_octets_to_client{user="hello"} 80942127840 (75.38 GB)
telemt_user_unique_ips_current{user="hello"} 46
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 52011.9 (14h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 641633
telemt_connections_bad_total 156154
telemt_handshake_timeouts_total 20087
telemt_upstream_connect_attempt_total 78410
telemt_upstream_connect_success_total 77961
telemt_upstream_connect_fail_total 215
telemt_upstream_connect_attempts_per_request{bucket="1"} 77960
telemt_upstream_connect_attempts_per_request{bucket="2"} 216
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45693
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32052
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 216
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 215
telemt_me_keepalive_timeout_total 1025
telemt_me_reconnect_attempts_total 36930
telemt_me_reconnect_success_total 36840
telemt_me_reader_eof_total 38810
telemt_me_idle_close_by_peer_total 38806
telemt_me_route_drop_no_conn_total 241642
telemt_me_hardswap_pending_ttl_expired_total 15
telemt_me_single_endpoint_shadow_rotate_total 216
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1138
telemt_desync_full_logged_total 405
telemt_desync_suppressed_total 733
telemt_desync_frames_bucket_total{bucket="1_2"} 342
telemt_desync_frames_bucket_total{bucket="3_10"} 377
telemt_desync_frames_bucket_total{bucket="gt_10"} 419
telemt_pool_swap_total 5
telemt_pool_force_close_total 294
telemt_me_writer_removed_unexpected_total 38822
telemt_me_writer_restored_same_endpoint_total 36819
telemt_me_writer_removed_unexpected_minus_restored_total 2003
telemt_user_connections_total{user="hello"} 446017
telemt_user_connections_current{user="hello"} 535
telemt_user_octets_from_client{user="hello"} 5870845468 (5.47 GB)
telemt_user_octets_to_client{user="hello"} 148579610092 (138.38 GB)
telemt_user_unique_ips_current{user="hello"} 73
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 52010.6 (14h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 415963
telemt_connections_bad_total 28918
telemt_handshake_timeouts_total 66589
telemt_upstream_connect_attempt_total 38410
telemt_upstream_connect_success_total 38257
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 38257
telemt_upstream_connect_attempts_per_request{bucket="2"} 75
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23711
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14545
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 428
telemt_me_reconnect_attempts_total 8217
telemt_me_reconnect_success_total 8189
telemt_me_reader_eof_total 8372
telemt_me_idle_close_by_peer_total 8372
telemt_me_route_drop_no_conn_total 118813
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_single_endpoint_shadow_rotate_total 213
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 233
telemt_desync_full_logged_total 98
telemt_desync_suppressed_total 135
telemt_desync_frames_bucket_total{bucket="1_2"} 56
telemt_desync_frames_bucket_total{bucket="3_10"} 98
telemt_desync_frames_bucket_total{bucket="gt_10"} 79
telemt_pool_swap_total 14
telemt_pool_force_close_total 375
telemt_me_writer_removed_unexpected_total 8372
telemt_me_writer_restored_same_endpoint_total 8168
telemt_me_writer_removed_unexpected_minus_restored_total 204
telemt_user_connections_total{user="hello"} 298104
telemt_user_connections_current{user="hello"} 453
telemt_user_octets_from_client{user="hello"} 3651828784 (3.40 GB)
telemt_user_octets_to_client{user="hello"} 110756116752 (103.15 GB)
telemt_user_unique_ips_current{user="hello"} 56
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 52009.6 (14h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 560458
telemt_connections_bad_total 6817
telemt_handshake_timeouts_total 132463
telemt_upstream_connect_attempt_total 73962
telemt_upstream_connect_success_total 73457
telemt_upstream_connect_fail_total 240
telemt_upstream_connect_attempts_per_request{bucket="1"} 73457
telemt_upstream_connect_attempts_per_request{bucket="2"} 240
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44277
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28981
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 197
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 240
telemt_me_keepalive_timeout_total 968
telemt_me_reconnect_attempts_total 35597
telemt_me_reconnect_success_total 35562
telemt_me_reader_eof_total 37305
telemt_me_idle_close_by_peer_total 37304
telemt_me_route_drop_no_conn_total 179366
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 15
telemt_me_single_endpoint_shadow_rotate_total 218
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 819
telemt_desync_full_logged_total 257
telemt_desync_suppressed_total 562
telemt_desync_frames_bucket_total{bucket="1_2"} 145
telemt_desync_frames_bucket_total{bucket="3_10"} 344
telemt_desync_frames_bucket_total{bucket="gt_10"} 330
telemt_pool_swap_total 6
telemt_pool_force_close_total 263
telemt_pool_stale_pick_total 2870
telemt_me_writer_removed_unexpected_total 37317
telemt_me_writer_restored_same_endpoint_total 35537
telemt_me_writer_removed_unexpected_minus_restored_total 1780
telemt_user_connections_total{user="hello"} 396273
telemt_user_connections_current{user="hello"} 635
telemt_user_octets_from_client{user="hello"} 5153005536 (4.80 GB)
telemt_user_octets_to_client{user="hello"} 108820456724 (101.35 GB)
telemt_user_connections_total{user="hello2"} 1
telemt_user_octets_from_client{user="hello2"} 140 (140 B)
telemt_user_octets_to_client{user="hello2"} 104 (104 B)
telemt_user_unique_ips_current{user="hello"} 63
```