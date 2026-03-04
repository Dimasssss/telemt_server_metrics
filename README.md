# Server Metrics 2026-03-04 05:28:26 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 29867.9 (8h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 222990
telemt_connections_bad_total 2306
telemt_handshake_timeouts_total 4481
telemt_upstream_connect_attempt_total 20790
telemt_upstream_connect_success_total 20697
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 20697
telemt_upstream_connect_attempts_per_request{bucket="2"} 41
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11760
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8908
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 12
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_keepalive_timeout_total 219
telemt_me_reconnect_attempts_total 4600
telemt_me_reconnect_success_total 4581
telemt_me_reader_eof_total 4686
telemt_me_idle_close_by_peer_total 4686
telemt_me_route_drop_no_conn_total 72140
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 122
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 592
telemt_desync_full_logged_total 219
telemt_desync_suppressed_total 373
telemt_desync_frames_bucket_total{bucket="1_2"} 165
telemt_desync_frames_bucket_total{bucket="3_10"} 206
telemt_desync_frames_bucket_total{bucket="gt_10"} 221
telemt_pool_swap_total 7
telemt_pool_force_close_total 218
telemt_me_writer_removed_unexpected_total 4686
telemt_me_writer_restored_same_endpoint_total 4561
telemt_me_writer_removed_unexpected_minus_restored_total 125
telemt_user_connections_total{user="hello"} 210600
telemt_user_connections_current{user="hello"} 722
telemt_user_octets_from_client{user="hello"} 2198842012 (2.05 GB)
telemt_user_octets_to_client{user="hello"} 70272934380 (65.45 GB)
telemt_user_unique_ips_current{user="hello"} 78
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 29864.5 (8h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 104378
telemt_connections_bad_total 353
telemt_handshake_timeouts_total 21805
telemt_upstream_connect_attempt_total 67216
telemt_upstream_connect_success_total 66443
telemt_upstream_connect_fail_total 370
telemt_upstream_connect_attempts_per_request{bucket="1"} 66437
telemt_upstream_connect_attempts_per_request{bucket="2"} 376
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45076
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21347
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 370
telemt_me_keepalive_timeout_total 998
telemt_me_reconnect_attempts_total 40544
telemt_me_reconnect_success_total 40516
telemt_me_reader_eof_total 41529
telemt_me_idle_close_by_peer_total 41528
telemt_me_route_drop_no_conn_total 32856
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_single_endpoint_shadow_rotate_total 131
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 222
telemt_desync_full_logged_total 90
telemt_desync_suppressed_total 132
telemt_desync_frames_bucket_total{bucket="1_2"} 53
telemt_desync_frames_bucket_total{bucket="3_10"} 119
telemt_desync_frames_bucket_total{bucket="gt_10"} 50
telemt_pool_swap_total 1
telemt_pool_force_close_total 75
telemt_me_writer_removed_unexpected_total 41590
telemt_me_writer_restored_same_endpoint_total 40495
telemt_me_writer_removed_unexpected_minus_restored_total 1095
telemt_user_connections_total{user="hello"} 76405
telemt_user_connections_current{user="hello"} 253
telemt_user_octets_from_client{user="hello"} 675830268 (644.52 MB)
telemt_user_octets_to_client{user="hello"} 32060378100 (29.86 GB)
telemt_user_unique_ips_current{user="hello"} 20
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 29863.3 (8h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 234012
telemt_connections_bad_total 85890
telemt_handshake_timeouts_total 4972
telemt_upstream_connect_attempt_total 39293
telemt_upstream_connect_success_total 39042
telemt_upstream_connect_fail_total 117
telemt_upstream_connect_attempts_per_request{bucket="1"} 39042
telemt_upstream_connect_attempts_per_request{bucket="2"} 117
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22892
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16030
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 120
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 117
telemt_me_keepalive_timeout_total 513
telemt_me_reconnect_attempts_total 15804
telemt_me_reconnect_success_total 15762
telemt_me_reader_eof_total 16601
telemt_me_idle_close_by_peer_total 16598
telemt_me_route_drop_no_conn_total 48093
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_single_endpoint_shadow_rotate_total 127
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 344
telemt_desync_full_logged_total 126
telemt_desync_suppressed_total 218
telemt_desync_frames_bucket_total{bucket="1_2"} 81
telemt_desync_frames_bucket_total{bucket="3_10"} 129
telemt_desync_frames_bucket_total{bucket="gt_10"} 134
telemt_pool_swap_total 3
telemt_pool_force_close_total 113
telemt_me_writer_removed_unexpected_total 16609
telemt_me_writer_restored_same_endpoint_total 15741
telemt_me_writer_removed_unexpected_minus_restored_total 868
telemt_user_connections_total{user="hello"} 138590
telemt_user_connections_current{user="hello"} 347
telemt_user_octets_from_client{user="hello"} 997801144 (951.58 MB)
telemt_user_octets_to_client{user="hello"} 36475637164 (33.97 GB)
telemt_user_unique_ips_current{user="hello"} 43
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 29862.3 (8h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 118366
telemt_connections_bad_total 8318
telemt_handshake_timeouts_total 1598
telemt_upstream_connect_attempt_total 21512
telemt_upstream_connect_success_total 21423
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 21423
telemt_upstream_connect_attempts_per_request{bucket="2"} 44
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13352
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8070
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_keepalive_timeout_total 218
telemt_me_reconnect_attempts_total 3816
telemt_me_reconnect_success_total 3814
telemt_me_reader_eof_total 3858
telemt_me_idle_close_by_peer_total 3858
telemt_me_route_drop_no_conn_total 36693
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 127
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 125
telemt_desync_full_logged_total 53
telemt_desync_suppressed_total 72
telemt_desync_frames_bucket_total{bucket="1_2"} 27
telemt_desync_frames_bucket_total{bucket="3_10"} 70
telemt_desync_frames_bucket_total{bucket="gt_10"} 28
telemt_pool_swap_total 8
telemt_pool_force_close_total 184
telemt_me_writer_removed_unexpected_total 3858
telemt_me_writer_restored_same_endpoint_total 3793
telemt_me_writer_removed_unexpected_minus_restored_total 65
telemt_user_connections_total{user="hello"} 102737
telemt_user_connections_current{user="hello"} 265
telemt_user_octets_from_client{user="hello"} 902439240 (860.63 MB)
telemt_user_octets_to_client{user="hello"} 37374426092 (34.81 GB)
telemt_user_unique_ips_current{user="hello"} 23
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 29860.9 (8h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 251026
telemt_connections_bad_total 5432
telemt_handshake_timeouts_total 113111
telemt_upstream_connect_attempt_total 44361
telemt_upstream_connect_success_total 44066
telemt_upstream_connect_fail_total 138
telemt_upstream_connect_attempts_per_request{bucket="1"} 44066
telemt_upstream_connect_attempts_per_request{bucket="2"} 138
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26104
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17854
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 106
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 138
telemt_me_keepalive_timeout_total 606
telemt_me_reconnect_attempts_total 21371
telemt_me_reconnect_success_total 21360
telemt_me_reader_eof_total 22542
telemt_me_idle_close_by_peer_total 22541
telemt_me_route_drop_no_conn_total 57488
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_single_endpoint_shadow_rotate_total 128
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 182
telemt_desync_full_logged_total 55
telemt_desync_suppressed_total 127
telemt_desync_frames_bucket_total{bucket="1_2"} 26
telemt_desync_frames_bucket_total{bucket="3_10"} 97
telemt_desync_frames_bucket_total{bucket="gt_10"} 59
telemt_pool_swap_total 4
telemt_pool_force_close_total 87
telemt_pool_stale_pick_total 2751
telemt_me_writer_removed_unexpected_total 22555
telemt_me_writer_restored_same_endpoint_total 21336
telemt_me_writer_removed_unexpected_minus_restored_total 1219
telemt_user_connections_total{user="hello"} 128078
telemt_user_connections_current{user="hello"} 191
telemt_user_octets_from_client{user="hello"} 1023598684 (976.18 MB)
telemt_user_octets_to_client{user="hello"} 29476419292 (27.45 GB)
telemt_user_unique_ips_current{user="hello"} 24
```