# Server Metrics 2026-03-04 13:04:45 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 57247.6 (15h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1004838
telemt_connections_bad_total 13009
telemt_handshake_timeouts_total 15837
telemt_upstream_connect_attempt_total 33892
telemt_upstream_connect_success_total 33745
telemt_upstream_connect_fail_total 59
telemt_upstream_connect_attempts_per_request{bucket="1"} 33745
telemt_upstream_connect_attempts_per_request{bucket="2"} 59
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18585
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15106
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 29
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 59
telemt_me_keepalive_timeout_total 378
telemt_me_reconnect_attempts_total 7125
telemt_me_reconnect_success_total 7075
telemt_me_reader_eof_total 7295
telemt_me_idle_close_by_peer_total 7295
telemt_me_route_drop_no_conn_total 363002
telemt_me_route_drop_channel_closed_total 3
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_single_endpoint_shadow_rotate_total 225
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1621
telemt_desync_full_logged_total 550
telemt_desync_suppressed_total 1071
telemt_desync_frames_bucket_total{bucket="1_2"} 461
telemt_desync_frames_bucket_total{bucket="3_10"} 617
telemt_desync_frames_bucket_total{bucket="gt_10"} 543
telemt_pool_swap_total 15
telemt_pool_force_close_total 576
telemt_pool_stale_pick_total 76
telemt_me_writer_removed_unexpected_total 7295
telemt_me_writer_restored_same_endpoint_total 7053
telemt_me_writer_removed_unexpected_minus_restored_total 242
telemt_user_connections_total{user="hello"} 792312
telemt_user_connections_current{user="hello"} 1208
telemt_user_octets_from_client{user="hello"} 8970231508 (8.35 GB)
telemt_user_octets_to_client{user="hello"} 256092421788 (238.50 GB)
telemt_user_unique_ips_current{user="hello"} 93
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 57242.6 (15h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 392317
telemt_connections_bad_total 3272
telemt_handshake_timeouts_total 28685
telemt_upstream_connect_attempt_total 103757
telemt_upstream_connect_success_total 102167
telemt_upstream_connect_fail_total 757
telemt_upstream_connect_attempts_per_request{bucket="1"} 102161
telemt_upstream_connect_attempts_per_request{bucket="2"} 763
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 68010
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34133
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 757
telemt_me_keepalive_timeout_total 1424
telemt_me_reconnect_attempts_total 57437
telemt_me_reconnect_success_total 57346
telemt_me_reader_eof_total 58789
telemt_me_idle_close_by_peer_total 58788
telemt_me_route_drop_no_conn_total 160375
telemt_me_hardswap_pending_ttl_expired_total 17
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 241
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
telemt_me_writer_removed_unexpected_total 58869
telemt_me_writer_restored_same_endpoint_total 57321
telemt_me_writer_removed_unexpected_minus_restored_total 1548
telemt_user_connections_total{user="hello"} 300402
telemt_user_connections_current{user="hello"} 424
telemt_user_octets_from_client{user="hello"} 3966629980 (3.69 GB)
telemt_user_octets_to_client{user="hello"} 95576612032 (89.01 GB)
telemt_user_unique_ips_current{user="hello"} 41
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 57241.3 (15h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 758768
telemt_connections_bad_total 170674
telemt_handshake_timeouts_total 25740
telemt_upstream_connect_attempt_total 81613
telemt_upstream_connect_success_total 81100
telemt_upstream_connect_fail_total 247
telemt_upstream_connect_attempts_per_request{bucket="1"} 81099
telemt_upstream_connect_attempts_per_request{bucket="2"} 248
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 47790
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33089
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 221
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 247
telemt_me_keepalive_timeout_total 1063
telemt_me_reconnect_attempts_total 37667
telemt_me_reconnect_success_total 37571
telemt_me_reader_eof_total 39561
telemt_me_idle_close_by_peer_total 39557
telemt_me_route_drop_no_conn_total 279480
telemt_me_hardswap_pending_ttl_expired_total 16
telemt_me_single_endpoint_shadow_rotate_total 238
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1393
telemt_desync_full_logged_total 484
telemt_desync_suppressed_total 909
telemt_desync_frames_bucket_total{bucket="1_2"} 421
telemt_desync_frames_bucket_total{bucket="3_10"} 461
telemt_desync_frames_bucket_total{bucket="gt_10"} 511
telemt_pool_swap_total 6
telemt_pool_force_close_total 331
telemt_me_writer_removed_unexpected_total 39573
telemt_me_writer_restored_same_endpoint_total 37549
telemt_me_writer_removed_unexpected_minus_restored_total 2024
telemt_user_connections_total{user="hello"} 527758
telemt_user_connections_current{user="hello"} 521
telemt_user_octets_from_client{user="hello"} 11772800904 (10.96 GB)
telemt_user_octets_to_client{user="hello"} 176353396992 (164.24 GB)
telemt_user_unique_ips_current{user="hello"} 60
```

## server4

```
telemt 3.2.1

telemt_uptime_seconds 3918.9 (1h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 47653
telemt_connections_bad_total 4658
telemt_handshake_timeouts_total 786
telemt_upstream_connect_attempt_total 1403
telemt_upstream_connect_success_total 1403
telemt_upstream_connect_attempts_per_request{bucket="1"} 1403
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 863
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 540
telemt_me_keepalive_timeout_total 14
telemt_me_reconnect_attempts_total 95
telemt_me_reconnect_success_total 114
telemt_me_reader_eof_total 95
telemt_me_idle_close_by_peer_total 95
telemt_me_route_drop_no_conn_total 16474
telemt_me_single_endpoint_shadow_rotate_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 53
telemt_desync_full_logged_total 21
telemt_desync_suppressed_total 32
telemt_desync_frames_bucket_total{bucket="1_2"} 17
telemt_desync_frames_bucket_total{bucket="3_10"} 10
telemt_desync_frames_bucket_total{bucket="gt_10"} 26
telemt_pool_swap_total 1
telemt_pool_force_close_total 41
telemt_me_writer_removed_unexpected_total 95
telemt_me_writer_restored_same_endpoint_total 93
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 41563
telemt_user_connections_current{user="hello"} 543
telemt_user_octets_from_client{user="hello"} 741657960 (707.30 MB)
telemt_user_octets_to_client{user="hello"} 28062798756 (26.14 GB)
telemt_user_unique_ips_current{user="hello"} 60
```

## server5

```
telemt 3.2.1

telemt_uptime_seconds 4278.2 (1h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 78355
telemt_connections_bad_total 70
telemt_handshake_timeouts_total 1223
telemt_upstream_connect_attempt_total 2067
telemt_upstream_connect_success_total 2054
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 2054
telemt_upstream_connect_attempts_per_request{bucket="2"} 6
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1249
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 801
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 217
telemt_me_reconnect_success_total 231
telemt_me_reader_eof_total 217
telemt_me_idle_close_by_peer_total 217
telemt_me_route_drop_no_conn_total 24275
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 219
telemt_desync_full_logged_total 84
telemt_desync_suppressed_total 135
telemt_desync_frames_bucket_total{bucket="1_2"} 30
telemt_desync_frames_bucket_total{bucket="3_10"} 90
telemt_desync_frames_bucket_total{bucket="gt_10"} 99
telemt_me_writer_removed_unexpected_total 217
telemt_me_writer_restored_same_endpoint_total 211
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 67161
telemt_user_connections_current{user="hello"} 598
telemt_user_octets_from_client{user="hello"} 737311768 (703.16 MB)
telemt_user_octets_to_client{user="hello"} 18415733596 (17.15 GB)
telemt_user_unique_ips_current{user="hello"} 68
```