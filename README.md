# Server Metrics 2026-03-04 01:22:46 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 15127.4 (4h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 101639
telemt_connections_bad_total 1366
telemt_handshake_timeouts_total 522
telemt_upstream_connect_attempt_total 11806
telemt_upstream_connect_success_total 11755
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 11755
telemt_upstream_connect_attempts_per_request{bucket="2"} 21
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6587
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5148
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 122
telemt_me_reconnect_attempts_total 3001
telemt_me_reconnect_success_total 3003
telemt_me_reader_eof_total 3067
telemt_me_idle_close_by_peer_total 3067
telemt_me_route_drop_no_conn_total 38089
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 62
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 145
telemt_desync_full_logged_total 49
telemt_desync_suppressed_total 96
telemt_desync_frames_bucket_total{bucket="1_2"} 49
telemt_desync_frames_bucket_total{bucket="3_10"} 48
telemt_desync_frames_bucket_total{bucket="gt_10"} 48
telemt_pool_swap_total 2
telemt_pool_force_close_total 78
telemt_me_writer_removed_unexpected_total 3067
telemt_me_writer_restored_same_endpoint_total 2983
telemt_me_writer_removed_unexpected_minus_restored_total 84
telemt_user_connections_total{user="hello"} 97417
telemt_user_connections_current{user="hello"} 321
telemt_user_octets_from_client{user="hello"} 732864796 (698.91 MB)
telemt_user_octets_to_client{user="hello"} 29811776180 (27.76 GB)
telemt_user_unique_ips_current{user="hello"} 49
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 15124.1 (4h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 47480
telemt_connections_bad_total 111
telemt_handshake_timeouts_total 11750
telemt_upstream_connect_attempt_total 31194
telemt_upstream_connect_success_total 30824
telemt_upstream_connect_fail_total 169
telemt_upstream_connect_attempts_per_request{bucket="1"} 30818
telemt_upstream_connect_attempts_per_request{bucket="2"} 175
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21009
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9797
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 169
telemt_me_keepalive_timeout_total 664
telemt_me_reconnect_attempts_total 17911
telemt_me_reconnect_success_total 17901
telemt_me_reader_eof_total 18345
telemt_me_idle_close_by_peer_total 18344
telemt_me_route_drop_no_conn_total 16831
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 65
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 79
telemt_desync_full_logged_total 34
telemt_desync_suppressed_total 45
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 31
telemt_desync_frames_bucket_total{bucket="gt_10"} 36
telemt_me_writer_removed_unexpected_total 18406
telemt_me_writer_restored_same_endpoint_total 17881
telemt_me_writer_removed_unexpected_minus_restored_total 525
telemt_user_connections_total{user="hello"} 35064
telemt_user_connections_current{user="hello"} 137
telemt_user_octets_from_client{user="hello"} 248666736 (237.15 MB)
telemt_user_octets_to_client{user="hello"} 20663008408 (19.24 GB)
telemt_user_unique_ips_current{user="hello"} 19
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 15122.8 (4h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 110451
telemt_connections_bad_total 37963
telemt_handshake_timeouts_total 1976
telemt_upstream_connect_attempt_total 16875
telemt_upstream_connect_success_total 16770
telemt_upstream_connect_fail_total 48
telemt_upstream_connect_attempts_per_request{bucket="1"} 16770
telemt_upstream_connect_attempts_per_request{bucket="2"} 48
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9763
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6948
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 48
telemt_me_keepalive_timeout_total 211
telemt_me_reconnect_attempts_total 5770
telemt_me_reconnect_success_total 5764
telemt_me_reader_eof_total 6002
telemt_me_idle_close_by_peer_total 6000
telemt_me_route_drop_no_conn_total 21320
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 65
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 232
telemt_desync_full_logged_total 76
telemt_desync_suppressed_total 156
telemt_desync_frames_bucket_total{bucket="1_2"} 48
telemt_desync_frames_bucket_total{bucket="3_10"} 86
telemt_desync_frames_bucket_total{bucket="gt_10"} 98
telemt_pool_swap_total 2
telemt_pool_force_close_total 61
telemt_me_writer_removed_unexpected_total 6003
telemt_me_writer_restored_same_endpoint_total 5743
telemt_me_writer_removed_unexpected_minus_restored_total 260
telemt_user_connections_total{user="hello"} 69159
telemt_user_connections_current{user="hello"} 100
telemt_user_octets_from_client{user="hello"} 426237060 (406.49 MB)
telemt_user_octets_to_client{user="hello"} 17640031960 (16.43 GB)
telemt_user_unique_ips_current{user="hello"} 23
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 15121.9 (4h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 49467
telemt_connections_bad_total 170
telemt_handshake_timeouts_total 533
telemt_upstream_connect_attempt_total 9746
telemt_upstream_connect_success_total 9707
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 9707
telemt_upstream_connect_attempts_per_request{bucket="2"} 19
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5959
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3747
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 100
telemt_me_reconnect_attempts_total 1394
telemt_me_reconnect_success_total 1403
telemt_me_reader_eof_total 1407
telemt_me_idle_close_by_peer_total 1407
telemt_me_route_drop_no_conn_total 16973
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 64
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 16
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 10
telemt_desync_frames_bucket_total{bucket="3_10"} 5
telemt_desync_frames_bucket_total{bucket="gt_10"} 11
telemt_pool_swap_total 4
telemt_pool_force_close_total 101
telemt_me_writer_removed_unexpected_total 1407
telemt_me_writer_restored_same_endpoint_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 24
telemt_user_connections_total{user="hello"} 47940
telemt_user_connections_current{user="hello"} 173
telemt_user_octets_from_client{user="hello"} 413526612 (394.37 MB)
telemt_user_octets_to_client{user="hello"} 12718589020 (11.85 GB)
telemt_user_unique_ips_current{user="hello"} 30
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 15120.4 (4h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 119658
telemt_connections_bad_total 58
telemt_handshake_timeouts_total 52198
telemt_upstream_connect_attempt_total 23670
telemt_upstream_connect_success_total 23536
telemt_upstream_connect_fail_total 63
telemt_upstream_connect_attempts_per_request{bucket="1"} 23536
telemt_upstream_connect_attempts_per_request{bucket="2"} 63
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13440
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10043
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 63
telemt_me_keepalive_timeout_total 314
telemt_me_reconnect_attempts_total 12566
telemt_me_reconnect_success_total 12567
telemt_me_reader_eof_total 13379
telemt_me_idle_close_by_peer_total 13378
telemt_me_route_drop_no_conn_total 37702
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 66
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 90
telemt_desync_full_logged_total 19
telemt_desync_suppressed_total 71
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 45
telemt_desync_frames_bucket_total{bucket="gt_10"} 30
telemt_pool_swap_total 1
telemt_pool_force_close_total 30
telemt_me_writer_removed_unexpected_total 13384
telemt_me_writer_restored_same_endpoint_total 12543
telemt_me_writer_removed_unexpected_minus_restored_total 841
telemt_user_connections_total{user="hello"} 65205
telemt_user_connections_current{user="hello"} 136
telemt_user_octets_from_client{user="hello"} 313037376 (298.54 MB)
telemt_user_octets_to_client{user="hello"} 15562178436 (14.49 GB)
telemt_user_unique_ips_current{user="hello"} 15
```