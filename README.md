# Server Metrics 2026-03-04 12:54:29 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 56631.1 (15h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 988693
telemt_connections_bad_total 12662
telemt_handshake_timeouts_total 15749
telemt_upstream_connect_attempt_total 33591
telemt_upstream_connect_success_total 33447
telemt_upstream_connect_fail_total 59
telemt_upstream_connect_attempts_per_request{bucket="1"} 33447
telemt_upstream_connect_attempts_per_request{bucket="2"} 59
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18422
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14972
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 28
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 59
telemt_me_keepalive_timeout_total 377
telemt_me_reconnect_attempts_total 7116
telemt_me_reconnect_success_total 7066
telemt_me_reader_eof_total 7286
telemt_me_idle_close_by_peer_total 7286
telemt_me_route_drop_no_conn_total 357206
telemt_me_route_drop_channel_closed_total 3
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_single_endpoint_shadow_rotate_total 221
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1580
telemt_desync_full_logged_total 538
telemt_desync_suppressed_total 1042
telemt_desync_frames_bucket_total{bucket="1_2"} 451
telemt_desync_frames_bucket_total{bucket="3_10"} 607
telemt_desync_frames_bucket_total{bucket="gt_10"} 522
telemt_pool_swap_total 15
telemt_pool_force_close_total 576
telemt_pool_stale_pick_total 76
telemt_me_writer_removed_unexpected_total 7286
telemt_me_writer_restored_same_endpoint_total 7044
telemt_me_writer_removed_unexpected_minus_restored_total 242
telemt_user_connections_total{user="hello"} 777449
telemt_user_connections_current{user="hello"} 942
telemt_user_octets_from_client{user="hello"} 8325077392 (7.75 GB)
telemt_user_octets_to_client{user="hello"} 247216981712 (230.24 GB)
telemt_user_unique_ips_current{user="hello"} 74
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 56627.5 (15h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 386703
telemt_connections_bad_total 3271
telemt_handshake_timeouts_total 28587
telemt_upstream_connect_attempt_total 103091
telemt_upstream_connect_success_total 101501
telemt_upstream_connect_fail_total 757
telemt_upstream_connect_attempts_per_request{bucket="1"} 101495
telemt_upstream_connect_attempts_per_request{bucket="2"} 763
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 67650
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33827
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 757
telemt_me_keepalive_timeout_total 1418
telemt_me_reconnect_attempts_total 57262
telemt_me_reconnect_success_total 57171
telemt_me_reader_eof_total 58611
telemt_me_idle_close_by_peer_total 58610
telemt_me_route_drop_no_conn_total 157763
telemt_me_hardswap_pending_ttl_expired_total 17
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 237
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 769
telemt_desync_full_logged_total 238
telemt_desync_suppressed_total 531
telemt_desync_frames_bucket_total{bucket="1_2"} 144
telemt_desync_frames_bucket_total{bucket="3_10"} 327
telemt_desync_frames_bucket_total{bucket="gt_10"} 298
telemt_pool_swap_total 4
telemt_pool_force_close_total 280
telemt_pool_stale_pick_total 56
telemt_me_writer_removed_unexpected_total 58691
telemt_me_writer_restored_same_endpoint_total 57146
telemt_me_writer_removed_unexpected_minus_restored_total 1545
telemt_user_connections_total{user="hello"} 295041
telemt_user_connections_current{user="hello"} 393
telemt_user_octets_from_client{user="hello"} 3918213220 (3.65 GB)
telemt_user_octets_to_client{user="hello"} 94294775860 (87.82 GB)
telemt_user_unique_ips_current{user="hello"} 46
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 56626.5 (15h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 743911
telemt_connections_bad_total 168935
telemt_handshake_timeouts_total 24479
telemt_upstream_connect_attempt_total 81316
telemt_upstream_connect_success_total 80823
telemt_upstream_connect_fail_total 237
telemt_upstream_connect_attempts_per_request{bucket="1"} 80822
telemt_upstream_connect_attempts_per_request{bucket="2"} 238
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 47625
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32977
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 221
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 237
telemt_me_keepalive_timeout_total 1058
telemt_me_reconnect_attempts_total 37650
telemt_me_reconnect_success_total 37554
telemt_me_reader_eof_total 39543
telemt_me_idle_close_by_peer_total 39539
telemt_me_route_drop_no_conn_total 274561
telemt_me_hardswap_pending_ttl_expired_total 16
telemt_me_single_endpoint_shadow_rotate_total 234
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1346
telemt_desync_full_logged_total 473
telemt_desync_suppressed_total 873
telemt_desync_frames_bucket_total{bucket="1_2"} 401
telemt_desync_frames_bucket_total{bucket="3_10"} 444
telemt_desync_frames_bucket_total{bucket="gt_10"} 501
telemt_pool_swap_total 6
telemt_pool_force_close_total 331
telemt_me_writer_removed_unexpected_total 39555
telemt_me_writer_restored_same_endpoint_total 37532
telemt_me_writer_removed_unexpected_minus_restored_total 2023
telemt_user_connections_total{user="hello"} 518362
telemt_user_connections_current{user="hello"} 648
telemt_user_octets_from_client{user="hello"} 11624759812 (10.83 GB)
telemt_user_octets_to_client{user="hello"} 171252568292 (159.49 GB)
telemt_user_unique_ips_current{user="hello"} 74
```

## server4

```
telemt 3.2.1

telemt_uptime_seconds 3303.7 (0h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 39270
telemt_connections_bad_total 4113
telemt_handshake_timeouts_total 698
telemt_upstream_connect_attempt_total 1230
telemt_upstream_connect_success_total 1230
telemt_upstream_connect_attempts_per_request{bucket="1"} 1230
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 756
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 474
telemt_me_keepalive_timeout_total 13
telemt_me_reconnect_attempts_total 90
telemt_me_reconnect_success_total 109
telemt_me_reader_eof_total 90
telemt_me_idle_close_by_peer_total 90
telemt_me_route_drop_no_conn_total 13501
telemt_me_single_endpoint_shadow_rotate_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 26
telemt_desync_full_logged_total 13
telemt_desync_suppressed_total 13
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 5
telemt_desync_frames_bucket_total{bucket="gt_10"} 14
telemt_pool_swap_total 1
telemt_pool_force_close_total 41
telemt_me_writer_removed_unexpected_total 90
telemt_me_writer_restored_same_endpoint_total 88
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 33902
telemt_user_connections_current{user="hello"} 497
telemt_user_octets_from_client{user="hello"} 542042536 (516.93 MB)
telemt_user_octets_to_client{user="hello"} 21746062840 (20.25 GB)
telemt_user_unique_ips_current{user="hello"} 50
```

## server5

```
telemt 3.2.1

telemt_uptime_seconds 3663.1 (1h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 67587
telemt_connections_bad_total 13
telemt_handshake_timeouts_total 1070
telemt_upstream_connect_attempt_total 1536
telemt_upstream_connect_success_total 1525
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 1525
telemt_upstream_connect_attempts_per_request{bucket="2"} 4
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 901
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 622
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 16
telemt_me_reconnect_attempts_total 106
telemt_me_reconnect_success_total 120
telemt_me_reader_eof_total 101
telemt_me_idle_close_by_peer_total 101
telemt_me_route_drop_no_conn_total 20444
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 189
telemt_desync_full_logged_total 74
telemt_desync_suppressed_total 115
telemt_desync_frames_bucket_total{bucket="1_2"} 23
telemt_desync_frames_bucket_total{bucket="3_10"} 78
telemt_desync_frames_bucket_total{bucket="gt_10"} 88
telemt_me_writer_removed_unexpected_total 101
telemt_me_writer_restored_same_endpoint_total 100
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 57163
telemt_user_connections_current{user="hello"} 518
telemt_user_octets_from_client{user="hello"} 643290408 (613.49 MB)
telemt_user_octets_to_client{user="hello"} 16402919136 (15.28 GB)
telemt_user_unique_ips_current{user="hello"} 53
```