# Server Metrics 2026-03-04 03:10:14 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 21575.7 (5h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 136537
telemt_connections_bad_total 1385
telemt_handshake_timeouts_total 1879
telemt_upstream_connect_attempt_total 16959
telemt_upstream_connect_success_total 16888
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 16888
telemt_upstream_connect_attempts_per_request{bucket="2"} 31
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9510
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7355
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 175
telemt_me_reconnect_attempts_total 4239
telemt_me_reconnect_success_total 4230
telemt_me_reader_eof_total 4328
telemt_me_idle_close_by_peer_total 4328
telemt_me_route_drop_no_conn_total 47913
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 87
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 257
telemt_desync_full_logged_total 89
telemt_desync_suppressed_total 168
telemt_desync_frames_bucket_total{bucket="1_2"} 74
telemt_desync_frames_bucket_total{bucket="3_10"} 82
telemt_desync_frames_bucket_total{bucket="gt_10"} 101
telemt_pool_swap_total 4
telemt_pool_force_close_total 139
telemt_me_writer_removed_unexpected_total 4328
telemt_me_writer_restored_same_endpoint_total 4210
telemt_me_writer_removed_unexpected_minus_restored_total 118
telemt_user_connections_total{user="hello"} 130226
telemt_user_connections_current{user="hello"} 344
telemt_user_octets_from_client{user="hello"} 1151645316 (1.07 GB)
telemt_user_octets_to_client{user="hello"} 38529720080 (35.88 GB)
telemt_user_unique_ips_current{user="hello"} 58
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 21572.4 (5h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 64088
telemt_connections_bad_total 280
telemt_handshake_timeouts_total 16607
telemt_upstream_connect_attempt_total 53448
telemt_upstream_connect_success_total 52905
telemt_upstream_connect_fail_total 255
telemt_upstream_connect_attempts_per_request{bucket="1"} 52899
telemt_upstream_connect_attempts_per_request{bucket="2"} 261
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36131
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16755
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 255
telemt_me_keepalive_timeout_total 878
telemt_me_reconnect_attempts_total 33396
telemt_me_reconnect_success_total 33375
telemt_me_reader_eof_total 34218
telemt_me_idle_close_by_peer_total 34217
telemt_me_route_drop_no_conn_total 20890
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 95
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 104
telemt_desync_full_logged_total 45
telemt_desync_suppressed_total 59
telemt_desync_frames_bucket_total{bucket="1_2"} 16
telemt_desync_frames_bucket_total{bucket="3_10"} 48
telemt_desync_frames_bucket_total{bucket="gt_10"} 40
telemt_me_writer_removed_unexpected_total 34279
telemt_me_writer_restored_same_endpoint_total 33355
telemt_me_writer_removed_unexpected_minus_restored_total 924
telemt_user_connections_total{user="hello"} 46454
telemt_user_connections_current{user="hello"} 165
telemt_user_octets_from_client{user="hello"} 373578748 (356.27 MB)
telemt_user_octets_to_client{user="hello"} 24678834432 (22.98 GB)
telemt_user_unique_ips_current{user="hello"} 18
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 21571.3 (5h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 150828
telemt_connections_bad_total 54820
telemt_handshake_timeouts_total 3376
telemt_upstream_connect_attempt_total 27582
telemt_upstream_connect_success_total 27398
telemt_upstream_connect_fail_total 86
telemt_upstream_connect_attempts_per_request{bucket="1"} 27398
telemt_upstream_connect_attempts_per_request{bucket="2"} 86
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16074
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11241
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 83
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 86
telemt_me_keepalive_timeout_total 348
telemt_me_reconnect_attempts_total 10527
telemt_me_reconnect_success_total 10503
telemt_me_reader_eof_total 11009
telemt_me_idle_close_by_peer_total 11006
telemt_me_route_drop_no_conn_total 29346
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 91
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 290
telemt_desync_full_logged_total 101
telemt_desync_suppressed_total 189
telemt_desync_frames_bucket_total{bucket="1_2"} 60
telemt_desync_frames_bucket_total{bucket="3_10"} 107
telemt_desync_frames_bucket_total{bucket="gt_10"} 123
telemt_pool_swap_total 2
telemt_pool_force_close_total 63
telemt_me_writer_removed_unexpected_total 11011
telemt_me_writer_restored_same_endpoint_total 10482
telemt_me_writer_removed_unexpected_minus_restored_total 529
telemt_user_connections_total{user="hello"} 89217
telemt_user_connections_current{user="hello"} 190
telemt_user_octets_from_client{user="hello"} 552497048 (526.90 MB)
telemt_user_octets_to_client{user="hello"} 22247314404 (20.72 GB)
telemt_user_unique_ips_current{user="hello"} 22
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 21570.1 (5h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 68629
telemt_connections_bad_total 277
telemt_handshake_timeouts_total 658
telemt_upstream_connect_attempt_total 13798
telemt_upstream_connect_success_total 13729
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 13729
telemt_upstream_connect_attempts_per_request{bucket="2"} 34
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8519
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_keepalive_timeout_total 146
telemt_me_reconnect_attempts_total 1918
telemt_me_reconnect_success_total 1922
telemt_me_reader_eof_total 1930
telemt_me_idle_close_by_peer_total 1930
telemt_me_route_drop_no_conn_total 23498
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 89
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 38
telemt_desync_full_logged_total 17
telemt_desync_suppressed_total 21
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 15
telemt_desync_frames_bucket_total{bucket="gt_10"} 16
telemt_pool_swap_total 7
telemt_pool_force_close_total 157
telemt_me_writer_removed_unexpected_total 1930
telemt_me_writer_restored_same_endpoint_total 1901
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 66298
telemt_user_connections_current{user="hello"} 200
telemt_user_octets_from_client{user="hello"} 545539124 (520.27 MB)
telemt_user_octets_to_client{user="hello"} 23119237896 (21.53 GB)
telemt_user_unique_ips_current{user="hello"} 35
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 21568.8 (5h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 163702
telemt_connections_bad_total 117
telemt_handshake_timeouts_total 74405
telemt_upstream_connect_attempt_total 31894
telemt_upstream_connect_success_total 31697
telemt_upstream_connect_fail_total 94
telemt_upstream_connect_attempts_per_request{bucket="1"} 31697
telemt_upstream_connect_attempts_per_request{bucket="2"} 94
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18497
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13127
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 73
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 94
telemt_me_keepalive_timeout_total 419
telemt_me_reconnect_attempts_total 15794
telemt_me_reconnect_success_total 15790
telemt_me_reader_eof_total 16749
telemt_me_idle_close_by_peer_total 16748
telemt_me_route_drop_no_conn_total 44060
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 92
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 120
telemt_desync_full_logged_total 28
telemt_desync_suppressed_total 92
telemt_desync_frames_bucket_total{bucket="1_2"} 18
telemt_desync_frames_bucket_total{bucket="3_10"} 56
telemt_desync_frames_bucket_total{bucket="gt_10"} 46
telemt_pool_swap_total 2
telemt_pool_force_close_total 59
telemt_pool_stale_pick_total 2475
telemt_me_writer_removed_unexpected_total 16754
telemt_me_writer_restored_same_endpoint_total 15766
telemt_me_writer_removed_unexpected_minus_restored_total 988
telemt_user_connections_total{user="hello"} 86082
telemt_user_connections_current{user="hello"} 129
telemt_user_octets_from_client{user="hello"} 506706404 (483.23 MB)
telemt_user_octets_to_client{user="hello"} 19872492104 (18.51 GB)
telemt_user_unique_ips_current{user="hello"} 21
```