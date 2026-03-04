# Server Metrics 2026-03-04 03:46:03 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 23725.0 (6h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 153468
telemt_connections_bad_total 1538
telemt_handshake_timeouts_total 2574
telemt_upstream_connect_attempt_total 18034
telemt_upstream_connect_success_total 17959
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 17959
telemt_upstream_connect_attempts_per_request{bucket="2"} 33
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10110
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7826
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_keepalive_timeout_total 193
telemt_me_reconnect_attempts_total 4281
telemt_me_reconnect_success_total 4267
telemt_me_reader_eof_total 4368
telemt_me_idle_close_by_peer_total 4368
telemt_me_route_drop_no_conn_total 52184
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 98
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 356
telemt_desync_full_logged_total 130
telemt_desync_suppressed_total 226
telemt_desync_frames_bucket_total{bucket="1_2"} 92
telemt_desync_frames_bucket_total{bucket="3_10"} 127
telemt_desync_frames_bucket_total{bucket="gt_10"} 137
telemt_pool_swap_total 5
telemt_pool_force_close_total 168
telemt_me_writer_removed_unexpected_total 4368
telemt_me_writer_restored_same_endpoint_total 4247
telemt_me_writer_removed_unexpected_minus_restored_total 121
telemt_user_connections_total{user="hello"} 145920
telemt_user_connections_current{user="hello"} 337
telemt_user_octets_from_client{user="hello"} 1389741532 (1.29 GB)
telemt_user_octets_to_client{user="hello"} 45232449692 (42.13 GB)
telemt_user_unique_ips_current{user="hello"} 67
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 23721.6 (6h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 72668
telemt_connections_bad_total 289
telemt_handshake_timeouts_total 19183
telemt_upstream_connect_attempt_total 60536
telemt_upstream_connect_success_total 59946
telemt_upstream_connect_fail_total 279
telemt_upstream_connect_attempts_per_request{bucket="1"} 59940
telemt_upstream_connect_attempts_per_request{bucket="2"} 285
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40982
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18944
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 279
telemt_me_keepalive_timeout_total 943
telemt_me_reconnect_attempts_total 38378
telemt_me_reconnect_success_total 38354
telemt_me_reader_eof_total 39329
telemt_me_idle_close_by_peer_total 39328
telemt_me_route_drop_no_conn_total 23115
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
telemt_user_connections_total{user="hello"} 52324
telemt_user_connections_current{user="hello"} 190
telemt_user_octets_from_client{user="hello"} 429701548 (409.80 MB)
telemt_user_octets_to_client{user="hello"} 25962378228 (24.18 GB)
telemt_user_unique_ips_current{user="hello"} 44
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 23720.5 (6h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 165910
telemt_connections_bad_total 60439
telemt_handshake_timeouts_total 3768
telemt_upstream_connect_attempt_total 32889
telemt_upstream_connect_success_total 32676
telemt_upstream_connect_fail_total 99
telemt_upstream_connect_attempts_per_request{bucket="1"} 32676
telemt_upstream_connect_attempts_per_request{bucket="2"} 99
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19186
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13388
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 102
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 99
telemt_me_keepalive_timeout_total 437
telemt_me_reconnect_attempts_total 13835
telemt_me_reconnect_success_total 13804
telemt_me_reader_eof_total 14536
telemt_me_idle_close_by_peer_total 14533
telemt_me_route_drop_no_conn_total 32065
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
telemt_me_writer_removed_unexpected_total 14541
telemt_me_writer_restored_same_endpoint_total 13783
telemt_me_writer_removed_unexpected_minus_restored_total 758
telemt_user_connections_total{user="hello"} 98108
telemt_user_connections_current{user="hello"} 245
telemt_user_octets_from_client{user="hello"} 608659956 (580.46 MB)
telemt_user_octets_to_client{user="hello"} 25874011220 (24.10 GB)
telemt_user_unique_ips_current{user="hello"} 51
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 23719.4 (6h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 80167
telemt_connections_bad_total 2180
telemt_handshake_timeouts_total 755
telemt_upstream_connect_attempt_total 15430
telemt_upstream_connect_success_total 15355
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 15355
telemt_upstream_connect_attempts_per_request{bucket="2"} 37
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9456
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5898
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_keepalive_timeout_total 160
telemt_me_reconnect_attempts_total 2163
telemt_me_reconnect_success_total 2166
telemt_me_reader_eof_total 2180
telemt_me_idle_close_by_peer_total 2180
telemt_me_route_drop_no_conn_total 26419
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 101
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 96
telemt_desync_full_logged_total 36
telemt_desync_suppressed_total 60
telemt_desync_frames_bucket_total{bucket="1_2"} 22
telemt_desync_frames_bucket_total{bucket="3_10"} 54
telemt_desync_frames_bucket_total{bucket="gt_10"} 20
telemt_pool_swap_total 7
telemt_pool_force_close_total 157
telemt_me_writer_removed_unexpected_total 2180
telemt_me_writer_restored_same_endpoint_total 2145
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 73908
telemt_user_connections_current{user="hello"} 194
telemt_user_octets_from_client{user="hello"} 655892928 (625.51 MB)
telemt_user_octets_to_client{user="hello"} 25450947572 (23.70 GB)
telemt_user_unique_ips_current{user="hello"} 33
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 23718.0 (6h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 181034
telemt_connections_bad_total 121
telemt_handshake_timeouts_total 83397
telemt_upstream_connect_attempt_total 36672
telemt_upstream_connect_success_total 36449
telemt_upstream_connect_fail_total 103
telemt_upstream_connect_attempts_per_request{bucket="1"} 36449
telemt_upstream_connect_attempts_per_request{bucket="2"} 103
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21354
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15001
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 92
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 103
telemt_me_keepalive_timeout_total 512
telemt_me_reconnect_attempts_total 18616
telemt_me_reconnect_success_total 18609
telemt_me_reader_eof_total 19707
telemt_me_idle_close_by_peer_total 19706
telemt_me_route_drop_no_conn_total 46611
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 102
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 125
telemt_desync_full_logged_total 33
telemt_desync_suppressed_total 92
telemt_desync_frames_bucket_total{bucket="1_2"} 18
telemt_desync_frames_bucket_total{bucket="3_10"} 61
telemt_desync_frames_bucket_total{bucket="gt_10"} 46
telemt_pool_swap_total 3
telemt_pool_force_close_total 85
telemt_pool_stale_pick_total 2751
telemt_me_writer_removed_unexpected_total 19718
telemt_me_writer_restored_same_endpoint_total 18585
telemt_me_writer_removed_unexpected_minus_restored_total 1133
telemt_user_connections_total{user="hello"} 94117
telemt_user_connections_current{user="hello"} 102
telemt_user_octets_from_client{user="hello"} 555227892 (529.51 MB)
telemt_user_octets_to_client{user="hello"} 21801395148 (20.30 GB)
telemt_user_unique_ips_current{user="hello"} 29
```