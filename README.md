# Server Metrics 2026-03-04 15:43:35 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 66777.7 (18h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1258495
telemt_connections_bad_total 16631
telemt_handshake_timeouts_total 22387
telemt_upstream_connect_attempt_total 38772
telemt_upstream_connect_success_total 38594
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 38594
telemt_upstream_connect_attempts_per_request{bucket="2"} 69
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21230
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17284
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 46
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_keepalive_timeout_total 444
telemt_me_reconnect_attempts_total 8226
telemt_me_reconnect_success_total 8161
telemt_me_reader_eof_total 8431
telemt_me_idle_close_by_peer_total 8430
telemt_me_route_drop_no_conn_total 463793
telemt_me_route_drop_channel_closed_total 3
telemt_me_hardswap_pending_ttl_expired_total 15
telemt_me_single_endpoint_shadow_rotate_total 261
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 2523
telemt_desync_full_logged_total 813
telemt_desync_suppressed_total 1710
telemt_desync_frames_bucket_total{bucket="1_2"} 735
telemt_desync_frames_bucket_total{bucket="3_10"} 948
telemt_desync_frames_bucket_total{bucket="gt_10"} 840
telemt_pool_swap_total 17
telemt_pool_force_close_total 715
telemt_pool_stale_pick_total 76
telemt_me_writer_removed_unexpected_total 8431
telemt_me_writer_restored_same_endpoint_total 8139
telemt_me_writer_removed_unexpected_minus_restored_total 292
telemt_user_connections_total{user="hello"} 1017386
telemt_user_connections_current{user="hello"} 1033
telemt_user_octets_from_client{user="hello"} 13516669288 (12.59 GB)
telemt_user_octets_to_client{user="hello"} 343184989992 (319.62 GB)
telemt_user_unique_ips_current{user="hello"} 89
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 66774.2 (18h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 478149
telemt_connections_bad_total 4183
telemt_handshake_timeouts_total 30486
telemt_upstream_connect_attempt_total 121563
telemt_upstream_connect_success_total 119841
telemt_upstream_connect_fail_total 823
telemt_upstream_connect_attempts_per_request{bucket="1"} 119835
telemt_upstream_connect_attempts_per_request{bucket="2"} 829
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 77768
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 42049
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 823
telemt_me_keepalive_timeout_total 1594
telemt_me_reconnect_attempts_total 66410
telemt_me_reconnect_success_total 66305
telemt_me_reader_eof_total 68017
telemt_me_idle_close_by_peer_total 68016
telemt_me_route_drop_no_conn_total 194070
telemt_me_hardswap_pending_ttl_expired_total 21
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 278
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1196
telemt_desync_full_logged_total 358
telemt_desync_suppressed_total 838
telemt_desync_frames_bucket_total{bucket="1_2"} 221
telemt_desync_frames_bucket_total{bucket="3_10"} 466
telemt_desync_frames_bucket_total{bucket="gt_10"} 509
telemt_pool_swap_total 4
telemt_pool_force_close_total 281
telemt_pool_stale_pick_total 56
telemt_me_writer_removed_unexpected_total 68097
telemt_me_writer_restored_same_endpoint_total 66280
telemt_me_writer_removed_unexpected_minus_restored_total 1817
telemt_user_connections_total{user="hello"} 380006
telemt_user_connections_current{user="hello"} 447
telemt_user_octets_from_client{user="hello"} 5859760828 (5.46 GB)
telemt_user_octets_to_client{user="hello"} 120734859784 (112.44 GB)
telemt_user_unique_ips_current{user="hello"} 45
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 66773.1 (18h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 967232
telemt_connections_bad_total 197798
telemt_handshake_timeouts_total 30185
telemt_upstream_connect_attempt_total 88517
telemt_upstream_connect_success_total 87928
telemt_upstream_connect_fail_total 284
telemt_upstream_connect_attempts_per_request{bucket="1"} 87927
telemt_upstream_connect_attempts_per_request{bucket="2"} 285
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 51924
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35772
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 232
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 284
telemt_me_keepalive_timeout_total 1153
telemt_me_reconnect_attempts_total 39576
telemt_me_reconnect_success_total 39473
telemt_me_reader_eof_total 41540
telemt_me_idle_close_by_peer_total 41535
telemt_me_route_drop_no_conn_total 351269
telemt_me_hardswap_pending_ttl_expired_total 19
telemt_me_single_endpoint_shadow_rotate_total 274
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 2039
telemt_desync_full_logged_total 677
telemt_desync_suppressed_total 1362
telemt_desync_frames_bucket_total{bucket="1_2"} 624
telemt_desync_frames_bucket_total{bucket="3_10"} 658
telemt_desync_frames_bucket_total{bucket="gt_10"} 757
telemt_pool_swap_total 7
telemt_pool_force_close_total 381
telemt_me_writer_removed_unexpected_total 41553
telemt_me_writer_restored_same_endpoint_total 39451
telemt_me_writer_removed_unexpected_minus_restored_total 2102
telemt_user_connections_total{user="hello"} 693518
telemt_user_connections_current{user="hello"} 644
telemt_user_octets_from_client{user="hello"} 13992331412 (13.03 GB)
telemt_user_octets_to_client{user="hello"} 234325518240 (218.23 GB)
telemt_user_unique_ips_current{user="hello"} 71
```

## server4

```
telemt 3.2.1

telemt_uptime_seconds 13450.3 (3h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 212358
telemt_connections_bad_total 22530
telemt_handshake_timeouts_total 6078
telemt_upstream_connect_attempt_total 5469
telemt_upstream_connect_success_total 5469
telemt_upstream_connect_attempts_per_request{bucket="1"} 5469
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3201
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2268
telemt_me_keepalive_timeout_total 63
telemt_me_reconnect_attempts_total 861
telemt_me_reconnect_success_total 871
telemt_me_reader_eof_total 879
telemt_me_idle_close_by_peer_total 879
telemt_me_route_drop_no_conn_total 65218
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 53
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 220
telemt_desync_full_logged_total 81
telemt_desync_suppressed_total 139
telemt_desync_frames_bucket_total{bucket="1_2"} 70
telemt_desync_frames_bucket_total{bucket="3_10"} 55
telemt_desync_frames_bucket_total{bucket="gt_10"} 95
telemt_pool_swap_total 4
telemt_pool_force_close_total 146
telemt_me_writer_removed_unexpected_total 879
telemt_me_writer_restored_same_endpoint_total 850
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 176251
telemt_user_connections_current{user="hello"} 498
telemt_user_octets_from_client{user="hello"} 2188498664 (2.04 GB)
telemt_user_octets_to_client{user="hello"} 70129930744 (65.31 GB)
telemt_user_unique_ips_current{user="hello"} 45
```

## server5

```
telemt 3.2.1

telemt_uptime_seconds 13810.1 (3h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 238322
telemt_connections_bad_total 2507
telemt_handshake_timeouts_total 3640
telemt_upstream_connect_attempt_total 7092
telemt_upstream_connect_success_total 7055
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 7055
telemt_upstream_connect_attempts_per_request{bucket="2"} 18
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4087
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2958
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_keepalive_timeout_total 99
telemt_me_reconnect_attempts_total 1299
telemt_me_reconnect_success_total 1306
telemt_me_reader_eof_total 1332
telemt_me_idle_close_by_peer_total 1332
telemt_me_route_drop_no_conn_total 88745
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 59
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 514
telemt_desync_full_logged_total 197
telemt_desync_suppressed_total 317
telemt_desync_frames_bucket_total{bucket="1_2"} 76
telemt_desync_frames_bucket_total{bucket="3_10"} 220
telemt_desync_frames_bucket_total{bucket="gt_10"} 218
telemt_pool_swap_total 3
telemt_pool_force_close_total 139
telemt_me_writer_removed_unexpected_total 1332
telemt_me_writer_restored_same_endpoint_total 1286
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 203548
telemt_user_connections_current{user="hello"} 624
telemt_user_octets_from_client{user="hello"} 3291749164 (3.07 GB)
telemt_user_octets_to_client{user="hello"} 59846361516 (55.74 GB)
telemt_user_unique_ips_current{user="hello"} 60
```