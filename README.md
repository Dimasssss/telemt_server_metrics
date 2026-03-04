# Server Metrics 2026-03-04 12:59:36 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 56938.6 (15h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 996043
telemt_connections_bad_total 12737
telemt_handshake_timeouts_total 15808
telemt_upstream_connect_attempt_total 33755
telemt_upstream_connect_success_total 33609
telemt_upstream_connect_fail_total 59
telemt_upstream_connect_attempts_per_request{bucket="1"} 33609
telemt_upstream_connect_attempts_per_request{bucket="2"} 59
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18509
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15047
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 28
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 59
telemt_me_keepalive_timeout_total 378
telemt_me_reconnect_attempts_total 7122
telemt_me_reconnect_success_total 7072
telemt_me_reader_eof_total 7292
telemt_me_idle_close_by_peer_total 7292
telemt_me_route_drop_no_conn_total 359711
telemt_me_route_drop_channel_closed_total 3
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_single_endpoint_shadow_rotate_total 225
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1599
telemt_desync_full_logged_total 545
telemt_desync_suppressed_total 1054
telemt_desync_frames_bucket_total{bucket="1_2"} 456
telemt_desync_frames_bucket_total{bucket="3_10"} 610
telemt_desync_frames_bucket_total{bucket="gt_10"} 533
telemt_pool_swap_total 15
telemt_pool_force_close_total 576
telemt_pool_stale_pick_total 76
telemt_me_writer_removed_unexpected_total 7292
telemt_me_writer_restored_same_endpoint_total 7050
telemt_me_writer_removed_unexpected_minus_restored_total 242
telemt_user_connections_total{user="hello"} 784258
telemt_user_connections_current{user="hello"} 1128
telemt_user_octets_from_client{user="hello"} 8872301868 (8.26 GB)
telemt_user_octets_to_client{user="hello"} 251233810552 (233.98 GB)
telemt_user_unique_ips_current{user="hello"} 88
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 56935.0 (15h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 389303
telemt_connections_bad_total 3271
telemt_handshake_timeouts_total 28627
telemt_upstream_connect_attempt_total 103410
telemt_upstream_connect_success_total 101820
telemt_upstream_connect_fail_total 757
telemt_upstream_connect_attempts_per_request{bucket="1"} 101814
telemt_upstream_connect_attempts_per_request{bucket="2"} 763
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 67826
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33970
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 757
telemt_me_keepalive_timeout_total 1419
telemt_me_reconnect_attempts_total 57326
telemt_me_reconnect_success_total 57235
telemt_me_reader_eof_total 58675
telemt_me_idle_close_by_peer_total 58674
telemt_me_route_drop_no_conn_total 159082
telemt_me_hardswap_pending_ttl_expired_total 17
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 240
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
telemt_me_writer_removed_unexpected_total 58755
telemt_me_writer_restored_same_endpoint_total 57210
telemt_me_writer_removed_unexpected_minus_restored_total 1545
telemt_user_connections_total{user="hello"} 297547
telemt_user_connections_current{user="hello"} 410
telemt_user_octets_from_client{user="hello"} 3938303808 (3.67 GB)
telemt_user_octets_to_client{user="hello"} 94773506920 (88.26 GB)
telemt_user_unique_ips_current{user="hello"} 45
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 56933.9 (15h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 751248
telemt_connections_bad_total 169802
telemt_handshake_timeouts_total 24754
telemt_upstream_connect_attempt_total 81429
telemt_upstream_connect_success_total 80925
telemt_upstream_connect_fail_total 242
telemt_upstream_connect_attempts_per_request{bucket="1"} 80924
telemt_upstream_connect_attempts_per_request{bucket="2"} 243
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 47675
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33029
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 221
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 242
telemt_me_keepalive_timeout_total 1060
telemt_me_reconnect_attempts_total 37650
telemt_me_reconnect_success_total 37554
telemt_me_reader_eof_total 39543
telemt_me_idle_close_by_peer_total 39539
telemt_me_route_drop_no_conn_total 276570
telemt_me_hardswap_pending_ttl_expired_total 16
telemt_me_single_endpoint_shadow_rotate_total 237
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1368
telemt_desync_full_logged_total 480
telemt_desync_suppressed_total 888
telemt_desync_frames_bucket_total{bucket="1_2"} 410
telemt_desync_frames_bucket_total{bucket="3_10"} 449
telemt_desync_frames_bucket_total{bucket="gt_10"} 509
telemt_pool_swap_total 6
telemt_pool_force_close_total 331
telemt_me_writer_removed_unexpected_total 39555
telemt_me_writer_restored_same_endpoint_total 37532
telemt_me_writer_removed_unexpected_minus_restored_total 2023
telemt_user_connections_total{user="hello"} 522720
telemt_user_connections_current{user="hello"} 623
telemt_user_octets_from_client{user="hello"} 11665576372 (10.86 GB)
telemt_user_octets_to_client{user="hello"} 173048846252 (161.16 GB)
telemt_user_unique_ips_current{user="hello"} 68
```

## server4

```
telemt 3.2.1

telemt_uptime_seconds 3611.2 (1h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 43386
telemt_connections_bad_total 4381
telemt_handshake_timeouts_total 748
telemt_upstream_connect_attempt_total 1260
telemt_upstream_connect_success_total 1260
telemt_upstream_connect_attempts_per_request{bucket="1"} 1260
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 772
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 488
telemt_me_keepalive_timeout_total 14
telemt_me_reconnect_attempts_total 90
telemt_me_reconnect_success_total 109
telemt_me_reader_eof_total 90
telemt_me_idle_close_by_peer_total 90
telemt_me_route_drop_no_conn_total 14878
telemt_me_single_endpoint_shadow_rotate_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 50
telemt_desync_full_logged_total 19
telemt_desync_suppressed_total 31
telemt_desync_frames_bucket_total{bucket="1_2"} 17
telemt_desync_frames_bucket_total{bucket="3_10"} 10
telemt_desync_frames_bucket_total{bucket="gt_10"} 23
telemt_pool_swap_total 1
telemt_pool_force_close_total 41
telemt_me_writer_removed_unexpected_total 90
telemt_me_writer_restored_same_endpoint_total 88
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 37640
telemt_user_connections_current{user="hello"} 564
telemt_user_octets_from_client{user="hello"} 587728196 (560.50 MB)
telemt_user_octets_to_client{user="hello"} 24599603180 (22.91 GB)
telemt_user_unique_ips_current{user="hello"} 60
```

## server5

```
telemt 3.2.1

telemt_uptime_seconds 3970.6 (1h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 72599
telemt_connections_bad_total 57
telemt_handshake_timeouts_total 1178
telemt_upstream_connect_attempt_total 1822
telemt_upstream_connect_success_total 1809
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 1809
telemt_upstream_connect_attempts_per_request{bucket="2"} 6
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1076
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 729
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 155
telemt_me_reconnect_success_total 169
telemt_me_reader_eof_total 154
telemt_me_idle_close_by_peer_total 154
telemt_me_route_drop_no_conn_total 22191
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 204
telemt_desync_full_logged_total 79
telemt_desync_suppressed_total 125
telemt_desync_frames_bucket_total{bucket="1_2"} 27
telemt_desync_frames_bucket_total{bucket="3_10"} 83
telemt_desync_frames_bucket_total{bucket="gt_10"} 94
telemt_me_writer_removed_unexpected_total 154
telemt_me_writer_restored_same_endpoint_total 149
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 61845
telemt_user_connections_current{user="hello"} 513
telemt_user_octets_from_client{user="hello"} 685078660 (653.34 MB)
telemt_user_octets_to_client{user="hello"} 17176612548 (16.00 GB)
telemt_user_unique_ips_current{user="hello"} 55
```