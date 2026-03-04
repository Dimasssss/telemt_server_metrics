# Server Metrics 2026-03-04 04:16:46 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 25567.3 (7h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 170166
telemt_connections_bad_total 1617
telemt_handshake_timeouts_total 2983
telemt_upstream_connect_attempt_total 18714
telemt_upstream_connect_success_total 18631
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 18631
telemt_upstream_connect_attempts_per_request{bucket="2"} 37
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10525
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8083
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_keepalive_timeout_total 203
telemt_me_reconnect_attempts_total 4299
telemt_me_reconnect_success_total 4284
telemt_me_reader_eof_total 4386
telemt_me_idle_close_by_peer_total 4386
telemt_me_route_drop_no_conn_total 56560
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 106
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 423
telemt_desync_full_logged_total 151
telemt_desync_suppressed_total 272
telemt_desync_frames_bucket_total{bucket="1_2"} 111
telemt_desync_frames_bucket_total{bucket="3_10"} 151
telemt_desync_frames_bucket_total{bucket="gt_10"} 161
telemt_pool_swap_total 5
telemt_pool_force_close_total 168
telemt_me_writer_removed_unexpected_total 4386
telemt_me_writer_restored_same_endpoint_total 4264
telemt_me_writer_removed_unexpected_minus_restored_total 122
telemt_user_connections_total{user="hello"} 161690
telemt_user_connections_current{user="hello"} 622
telemt_user_octets_from_client{user="hello"} 1650654660 (1.54 GB)
telemt_user_octets_to_client{user="hello"} 50761498584 (47.28 GB)
telemt_user_unique_ips_current{user="hello"} 54
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 25564.0 (7h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 80347
telemt_connections_bad_total 299
telemt_handshake_timeouts_total 20614
telemt_upstream_connect_attempt_total 61381
telemt_upstream_connect_success_total 60747
telemt_upstream_connect_fail_total 301
telemt_upstream_connect_attempts_per_request{bucket="1"} 60741
telemt_upstream_connect_attempts_per_request{bucket="2"} 307
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41451
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19276
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 301
telemt_me_keepalive_timeout_total 948
telemt_me_reconnect_attempts_total 38451
telemt_me_reconnect_success_total 38424
telemt_me_reader_eof_total 39402
telemt_me_idle_close_by_peer_total 39401
telemt_me_route_drop_no_conn_total 25046
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_single_endpoint_shadow_rotate_total 112
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 190
telemt_desync_full_logged_total 78
telemt_desync_suppressed_total 112
telemt_desync_frames_bucket_total{bucket="1_2"} 41
telemt_desync_frames_bucket_total{bucket="3_10"} 102
telemt_desync_frames_bucket_total{bucket="gt_10"} 47
telemt_pool_swap_total 1
telemt_pool_force_close_total 75
telemt_me_writer_removed_unexpected_total 39463
telemt_me_writer_restored_same_endpoint_total 38403
telemt_me_writer_removed_unexpected_minus_restored_total 1060
telemt_user_connections_total{user="hello"} 58188
telemt_user_connections_current{user="hello"} 192
telemt_user_octets_from_client{user="hello"} 552685560 (527.08 MB)
telemt_user_octets_to_client{user="hello"} 27421693692 (25.54 GB)
telemt_user_unique_ips_current{user="hello"} 25
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 25562.9 (7h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 182699
telemt_connections_bad_total 66869
telemt_handshake_timeouts_total 4171
telemt_upstream_connect_attempt_total 33838
telemt_upstream_connect_success_total 33613
telemt_upstream_connect_fail_total 104
telemt_upstream_connect_attempts_per_request{bucket="1"} 33613
telemt_upstream_connect_attempts_per_request{bucket="2"} 104
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19758
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13748
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 107
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 104
telemt_me_keepalive_timeout_total 451
telemt_me_reconnect_attempts_total 13874
telemt_me_reconnect_success_total 13841
telemt_me_reader_eof_total 14576
telemt_me_idle_close_by_peer_total 14573
telemt_me_route_drop_no_conn_total 36299
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 110
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 301
telemt_desync_full_logged_total 107
telemt_desync_suppressed_total 194
telemt_desync_frames_bucket_total{bucket="1_2"} 64
telemt_desync_frames_bucket_total{bucket="3_10"} 109
telemt_desync_frames_bucket_total{bucket="gt_10"} 128
telemt_pool_swap_total 3
telemt_pool_force_close_total 113
telemt_me_writer_removed_unexpected_total 14581
telemt_me_writer_restored_same_endpoint_total 13820
telemt_me_writer_removed_unexpected_minus_restored_total 761
telemt_user_connections_total{user="hello"} 108016
telemt_user_connections_current{user="hello"} 210
telemt_user_octets_from_client{user="hello"} 697084808 (664.79 MB)
telemt_user_octets_to_client{user="hello"} 28067524720 (26.14 GB)
telemt_user_unique_ips_current{user="hello"} 30
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 25561.9 (7h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 90219
telemt_connections_bad_total 3806
telemt_handshake_timeouts_total 890
telemt_upstream_connect_attempt_total 17577
telemt_upstream_connect_success_total 17500
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 17500
telemt_upstream_connect_attempts_per_request{bucket="2"} 38
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10784
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6715
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_keepalive_timeout_total 185
telemt_me_reconnect_attempts_total 2812
telemt_me_reconnect_success_total 2813
telemt_me_reader_eof_total 2835
telemt_me_idle_close_by_peer_total 2835
telemt_me_route_drop_no_conn_total 29718
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 107
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 105
telemt_desync_full_logged_total 41
telemt_desync_suppressed_total 64
telemt_desync_frames_bucket_total{bucket="1_2"} 25
telemt_desync_frames_bucket_total{bucket="3_10"} 58
telemt_desync_frames_bucket_total{bucket="gt_10"} 22
telemt_pool_swap_total 8
telemt_pool_force_close_total 184
telemt_me_writer_removed_unexpected_total 2835
telemt_me_writer_restored_same_endpoint_total 2792
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 81536
telemt_user_connections_current{user="hello"} 166
telemt_user_octets_from_client{user="hello"} 698427724 (666.07 MB)
telemt_user_octets_to_client{user="hello"} 27610275564 (25.71 GB)
telemt_user_unique_ips_current{user="hello"} 34
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 25560.4 (7h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 200813
telemt_connections_bad_total 3374
telemt_handshake_timeouts_total 91912
telemt_upstream_connect_attempt_total 38016
telemt_upstream_connect_success_total 37748
telemt_upstream_connect_fail_total 125
telemt_upstream_connect_attempts_per_request{bucket="1"} 37748
telemt_upstream_connect_attempts_per_request{bucket="2"} 125
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22119
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15528
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 99
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 125
telemt_me_keepalive_timeout_total 535
telemt_me_reconnect_attempts_total 18820
telemt_me_reconnect_success_total 18812
telemt_me_reader_eof_total 19915
telemt_me_idle_close_by_peer_total 19914
telemt_me_route_drop_no_conn_total 48815
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 109
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 133
telemt_desync_full_logged_total 37
telemt_desync_suppressed_total 96
telemt_desync_frames_bucket_total{bucket="1_2"} 21
telemt_desync_frames_bucket_total{bucket="3_10"} 66
telemt_desync_frames_bucket_total{bucket="gt_10"} 46
telemt_pool_swap_total 3
telemt_pool_force_close_total 85
telemt_pool_stale_pick_total 2751
telemt_me_writer_removed_unexpected_total 19926
telemt_me_writer_restored_same_endpoint_total 18788
telemt_me_writer_removed_unexpected_minus_restored_total 1138
telemt_user_connections_total{user="hello"} 101840
telemt_user_connections_current{user="hello"} 188
telemt_user_octets_from_client{user="hello"} 650331312 (620.20 MB)
telemt_user_octets_to_client{user="hello"} 23098844272 (21.51 GB)
telemt_user_unique_ips_current{user="hello"} 25
```