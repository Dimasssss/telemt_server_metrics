# Server Metrics 2026-03-04 14:47:12 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 63395.2 (17h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1172154
telemt_connections_bad_total 14018
telemt_handshake_timeouts_total 21654
telemt_upstream_connect_attempt_total 37468
telemt_upstream_connect_success_total 37301
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 37301
telemt_upstream_connect_attempts_per_request{bucket="2"} 65
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20528
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16698
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 42
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_timeout_total 429
telemt_me_reconnect_attempts_total 8175
telemt_me_reconnect_success_total 8114
telemt_me_reader_eof_total 8379
telemt_me_idle_close_by_peer_total 8378
telemt_me_route_drop_no_conn_total 432746
telemt_me_route_drop_channel_closed_total 3
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_single_endpoint_shadow_rotate_total 248
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 2206
telemt_desync_full_logged_total 723
telemt_desync_suppressed_total 1483
telemt_desync_frames_bucket_total{bucket="1_2"} 655
telemt_desync_frames_bucket_total{bucket="3_10"} 835
telemt_desync_frames_bucket_total{bucket="gt_10"} 716
telemt_pool_swap_total 17
telemt_pool_force_close_total 715
telemt_pool_stale_pick_total 76
telemt_me_writer_removed_unexpected_total 8379
telemt_me_writer_restored_same_endpoint_total 8092
telemt_me_writer_removed_unexpected_minus_restored_total 287
telemt_user_connections_total{user="hello"} 938821
telemt_user_connections_current{user="hello"} 1036
telemt_user_octets_from_client{user="hello"} 12473928692 (11.62 GB)
telemt_user_octets_to_client{user="hello"} 314994475684 (293.36 GB)
telemt_user_unique_ips_current{user="hello"} 127
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 63391.5 (17h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 445673
telemt_connections_bad_total 3751
telemt_handshake_timeouts_total 29950
telemt_upstream_connect_attempt_total 114216
telemt_upstream_connect_success_total 112526
telemt_upstream_connect_fail_total 807
telemt_upstream_connect_attempts_per_request{bucket="1"} 112520
telemt_upstream_connect_attempts_per_request{bucket="2"} 813
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 73412
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39090
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 807
telemt_me_keepalive_timeout_total 1516
telemt_me_reconnect_attempts_total 62360
telemt_me_reconnect_success_total 62262
telemt_me_reader_eof_total 63888
telemt_me_idle_close_by_peer_total 63887
telemt_me_route_drop_no_conn_total 181320
telemt_me_hardswap_pending_ttl_expired_total 19
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 267
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1016
telemt_desync_full_logged_total 304
telemt_desync_suppressed_total 712
telemt_desync_frames_bucket_total{bucket="1_2"} 192
telemt_desync_frames_bucket_total{bucket="3_10"} 421
telemt_desync_frames_bucket_total{bucket="gt_10"} 403
telemt_pool_swap_total 4
telemt_pool_force_close_total 281
telemt_pool_stale_pick_total 56
telemt_me_writer_removed_unexpected_total 63968
telemt_me_writer_restored_same_endpoint_total 62237
telemt_me_writer_removed_unexpected_minus_restored_total 1731
telemt_user_connections_total{user="hello"} 349184
telemt_user_connections_current{user="hello"} 430
telemt_user_octets_from_client{user="hello"} 5489370980 (5.11 GB)
telemt_user_octets_to_client{user="hello"} 111260893912 (103.62 GB)
telemt_user_unique_ips_current{user="hello"} 45
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 63390.5 (17h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 894842
telemt_connections_bad_total 188210
telemt_handshake_timeouts_total 29557
telemt_upstream_connect_attempt_total 84756
telemt_upstream_connect_success_total 84200
telemt_upstream_connect_fail_total 268
telemt_upstream_connect_attempts_per_request{bucket="1"} 84199
telemt_upstream_connect_attempts_per_request{bucket="2"} 269
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 49777
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34198
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 225
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 268
telemt_me_keepalive_timeout_total 1099
telemt_me_reconnect_attempts_total 38110
telemt_me_reconnect_success_total 38011
telemt_me_reader_eof_total 40009
telemt_me_idle_close_by_peer_total 40005
telemt_me_route_drop_no_conn_total 325210
telemt_me_hardswap_pending_ttl_expired_total 18
telemt_me_single_endpoint_shadow_rotate_total 263
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1876
telemt_desync_full_logged_total 621
telemt_desync_suppressed_total 1255
telemt_desync_frames_bucket_total{bucket="1_2"} 591
telemt_desync_frames_bucket_total{bucket="3_10"} 598
telemt_desync_frames_bucket_total{bucket="gt_10"} 687
telemt_pool_swap_total 7
telemt_pool_force_close_total 381
telemt_me_writer_removed_unexpected_total 40021
telemt_me_writer_restored_same_endpoint_total 37989
telemt_me_writer_removed_unexpected_minus_restored_total 2032
telemt_user_connections_total{user="hello"} 633149
telemt_user_connections_current{user="hello"} 769
telemt_user_octets_from_client{user="hello"} 12903650448 (12.02 GB)
telemt_user_octets_to_client{user="hello"} 215524771080 (200.72 GB)
telemt_user_unique_ips_current{user="hello"} 71
```

## server4

```
telemt 3.2.1

telemt_uptime_seconds 10067.5 (2h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 146177
telemt_connections_bad_total 14014
telemt_handshake_timeouts_total 4883
telemt_upstream_connect_attempt_total 4716
telemt_upstream_connect_success_total 4716
telemt_upstream_connect_attempts_per_request{bucket="1"} 4716
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2902
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1814
telemt_me_keepalive_timeout_total 52
telemt_me_reconnect_attempts_total 851
telemt_me_reconnect_success_total 863
telemt_me_reader_eof_total 870
telemt_me_idle_close_by_peer_total 870
telemt_me_route_drop_no_conn_total 49269
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 44
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 180
telemt_desync_full_logged_total 70
telemt_desync_suppressed_total 110
telemt_desync_frames_bucket_total{bucket="1_2"} 46
telemt_desync_frames_bucket_total{bucket="3_10"} 54
telemt_desync_frames_bucket_total{bucket="gt_10"} 80
telemt_pool_swap_total 3
telemt_pool_force_close_total 110
telemt_me_writer_removed_unexpected_total 870
telemt_me_writer_restored_same_endpoint_total 842
telemt_me_writer_removed_unexpected_minus_restored_total 28
telemt_user_connections_total{user="hello"} 123086
telemt_user_connections_current{user="hello"} 543
telemt_user_octets_from_client{user="hello"} 1701641140 (1.58 GB)
telemt_user_octets_to_client{user="hello"} 59143626680 (55.08 GB)
telemt_user_unique_ips_current{user="hello"} 52
```

## server5

```
telemt 3.2.1

telemt_uptime_seconds 10427.1 (2h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 179551
telemt_connections_bad_total 1857
telemt_handshake_timeouts_total 2910
telemt_upstream_connect_attempt_total 5809
telemt_upstream_connect_success_total 5780
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 5780
telemt_upstream_connect_attempts_per_request{bucket="2"} 14
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3362
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2409
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 84
telemt_me_reconnect_attempts_total 1223
telemt_me_reconnect_success_total 1232
telemt_me_reader_eof_total 1257
telemt_me_idle_close_by_peer_total 1257
telemt_me_route_drop_no_conn_total 64810
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 44
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 450
telemt_desync_full_logged_total 169
telemt_desync_suppressed_total 281
telemt_desync_frames_bucket_total{bucket="1_2"} 58
telemt_desync_frames_bucket_total{bucket="3_10"} 194
telemt_desync_frames_bucket_total{bucket="gt_10"} 198
telemt_pool_swap_total 2
telemt_pool_force_close_total 101
telemt_me_writer_removed_unexpected_total 1257
telemt_me_writer_restored_same_endpoint_total 1212
telemt_me_writer_removed_unexpected_minus_restored_total 45
telemt_user_connections_total{user="hello"} 155294
telemt_user_connections_current{user="hello"} 625
telemt_user_octets_from_client{user="hello"} 1720085560 (1.60 GB)
telemt_user_octets_to_client{user="hello"} 42616229808 (39.69 GB)
telemt_user_unique_ips_current{user="hello"} 55
```