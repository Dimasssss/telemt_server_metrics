# Server Metrics 2026-03-04 03:51:10 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 24032.0 (6h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 156466
telemt_connections_bad_total 1617
telemt_handshake_timeouts_total 2841
telemt_upstream_connect_attempt_total 18072
telemt_upstream_connect_success_total 17997
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 17997
telemt_upstream_connect_attempts_per_request{bucket="2"} 33
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10129
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7845
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_keepalive_timeout_total 193
telemt_me_reconnect_attempts_total 4281
telemt_me_reconnect_success_total 4267
telemt_me_reader_eof_total 4368
telemt_me_idle_close_by_peer_total 4368
telemt_me_route_drop_no_conn_total 52732
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 98
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 376
telemt_desync_full_logged_total 135
telemt_desync_suppressed_total 241
telemt_desync_frames_bucket_total{bucket="1_2"} 96
telemt_desync_frames_bucket_total{bucket="3_10"} 136
telemt_desync_frames_bucket_total{bucket="gt_10"} 144
telemt_pool_swap_total 5
telemt_pool_force_close_total 168
telemt_me_writer_removed_unexpected_total 4368
telemt_me_writer_restored_same_endpoint_total 4247
telemt_me_writer_removed_unexpected_minus_restored_total 121
telemt_user_connections_total{user="hello"} 148540
telemt_user_connections_current{user="hello"} 483
telemt_user_octets_from_client{user="hello"} 1442706008 (1.34 GB)
telemt_user_octets_to_client{user="hello"} 46285744148 (43.11 GB)
telemt_user_unique_ips_current{user="hello"} 76
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 24028.7 (6h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 73959
telemt_connections_bad_total 290
telemt_handshake_timeouts_total 19581
telemt_upstream_connect_attempt_total 60593
telemt_upstream_connect_success_total 60003
telemt_upstream_connect_fail_total 279
telemt_upstream_connect_attempts_per_request{bucket="1"} 59997
telemt_upstream_connect_attempts_per_request{bucket="2"} 285
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41011
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18972
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 279
telemt_me_keepalive_timeout_total 943
telemt_me_reconnect_attempts_total 38378
telemt_me_reconnect_success_total 38354
telemt_me_reader_eof_total 39329
telemt_me_idle_close_by_peer_total 39328
telemt_me_route_drop_no_conn_total 23347
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_single_endpoint_shadow_rotate_total 105
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 186
telemt_desync_full_logged_total 75
telemt_desync_suppressed_total 111
telemt_desync_frames_bucket_total{bucket="1_2"} 41
telemt_desync_frames_bucket_total{bucket="3_10"} 100
telemt_desync_frames_bucket_total{bucket="gt_10"} 45
telemt_pool_swap_total 1
telemt_pool_force_close_total 75
telemt_me_writer_removed_unexpected_total 39390
telemt_me_writer_restored_same_endpoint_total 38334
telemt_me_writer_removed_unexpected_minus_restored_total 1056
telemt_user_connections_total{user="hello"} 53231
telemt_user_connections_current{user="hello"} 207
telemt_user_octets_from_client{user="hello"} 433783920 (413.69 MB)
telemt_user_octets_to_client{user="hello"} 26107054452 (24.31 GB)
telemt_user_unique_ips_current{user="hello"} 38
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 24027.5 (6h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 168333
telemt_connections_bad_total 61263
telemt_handshake_timeouts_total 3983
telemt_upstream_connect_attempt_total 32989
telemt_upstream_connect_success_total 32776
telemt_upstream_connect_fail_total 99
telemt_upstream_connect_attempts_per_request{bucket="1"} 32776
telemt_upstream_connect_attempts_per_request{bucket="2"} 99
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19250
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13424
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 102
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 99
telemt_me_keepalive_timeout_total 438
telemt_me_reconnect_attempts_total 13837
telemt_me_reconnect_success_total 13806
telemt_me_reader_eof_total 14538
telemt_me_idle_close_by_peer_total 14535
telemt_me_route_drop_no_conn_total 32524
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 102
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 297
telemt_desync_full_logged_total 104
telemt_desync_suppressed_total 193
telemt_desync_frames_bucket_total{bucket="1_2"} 60
telemt_desync_frames_bucket_total{bucket="3_10"} 109
telemt_desync_frames_bucket_total{bucket="gt_10"} 128
telemt_pool_swap_total 3
telemt_pool_force_close_total 113
telemt_me_writer_removed_unexpected_total 14543
telemt_me_writer_restored_same_endpoint_total 13785
telemt_me_writer_removed_unexpected_minus_restored_total 758
telemt_user_connections_total{user="hello"} 99518
telemt_user_connections_current{user="hello"} 260
telemt_user_octets_from_client{user="hello"} 614803300 (586.32 MB)
telemt_user_octets_to_client{user="hello"} 26258943080 (24.46 GB)
telemt_user_unique_ips_current{user="hello"} 43
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 24026.3 (6h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 81654
telemt_connections_bad_total 2450
telemt_handshake_timeouts_total 826
telemt_upstream_connect_attempt_total 15776
telemt_upstream_connect_success_total 15701
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 15701
telemt_upstream_connect_attempts_per_request{bucket="2"} 37
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9654
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6046
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_keepalive_timeout_total 164
telemt_me_reconnect_attempts_total 2247
telemt_me_reconnect_success_total 2250
telemt_me_reader_eof_total 2265
telemt_me_idle_close_by_peer_total 2265
telemt_me_route_drop_no_conn_total 26840
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 101
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 98
telemt_desync_full_logged_total 37
telemt_desync_suppressed_total 61
telemt_desync_frames_bucket_total{bucket="1_2"} 22
telemt_desync_frames_bucket_total{bucket="3_10"} 56
telemt_desync_frames_bucket_total{bucket="gt_10"} 20
telemt_pool_swap_total 7
telemt_pool_force_close_total 157
telemt_me_writer_removed_unexpected_total 2265
telemt_me_writer_restored_same_endpoint_total 2229
telemt_me_writer_removed_unexpected_minus_restored_total 36
telemt_user_connections_total{user="hello"} 75052
telemt_user_connections_current{user="hello"} 175
telemt_user_octets_from_client{user="hello"} 661930416 (631.27 MB)
telemt_user_octets_to_client{user="hello"} 25737713012 (23.97 GB)
telemt_user_unique_ips_current{user="hello"} 25
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 24025.0 (6h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 183509
telemt_connections_bad_total 122
telemt_handshake_timeouts_total 84770
telemt_upstream_connect_attempt_total 36806
telemt_upstream_connect_success_total 36583
telemt_upstream_connect_fail_total 103
telemt_upstream_connect_attempts_per_request{bucket="1"} 36583
telemt_upstream_connect_attempts_per_request{bucket="2"} 103
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21427
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15062
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 92
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 103
telemt_me_keepalive_timeout_total 514
telemt_me_reconnect_attempts_total 18620
telemt_me_reconnect_success_total 18612
telemt_me_reader_eof_total 19710
telemt_me_idle_close_by_peer_total 19709
telemt_me_route_drop_no_conn_total 46799
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 103
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 129
telemt_desync_full_logged_total 33
telemt_desync_suppressed_total 96
telemt_desync_frames_bucket_total{bucket="1_2"} 21
telemt_desync_frames_bucket_total{bucket="3_10"} 62
telemt_desync_frames_bucket_total{bucket="gt_10"} 46
telemt_pool_swap_total 3
telemt_pool_force_close_total 85
telemt_pool_stale_pick_total 2751
telemt_me_writer_removed_unexpected_total 19721
telemt_me_writer_restored_same_endpoint_total 18588
telemt_me_writer_removed_unexpected_minus_restored_total 1133
telemt_user_connections_total{user="hello"} 95176
telemt_user_connections_current{user="hello"} 136
telemt_user_octets_from_client{user="hello"} 561604388 (535.59 MB)
telemt_user_octets_to_client{user="hello"} 21917076724 (20.41 GB)
telemt_user_unique_ips_current{user="hello"} 25
```