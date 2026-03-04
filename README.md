# Server Metrics 2026-03-04 01:07:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 14206.3 (3h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 96899
telemt_connections_bad_total 687
telemt_handshake_timeouts_total 520
telemt_upstream_connect_attempt_total 10872
telemt_upstream_connect_success_total 10821
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 10821
telemt_upstream_connect_attempts_per_request{bucket="2"} 21
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6020
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4781
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 2777
telemt_me_reconnect_success_total 2779
telemt_me_reader_eof_total 2839
telemt_me_idle_close_by_peer_total 2839
telemt_me_route_drop_no_conn_total 36451
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 58
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 142
telemt_desync_full_logged_total 48
telemt_desync_suppressed_total 94
telemt_desync_frames_bucket_total{bucket="1_2"} 46
telemt_desync_frames_bucket_total{bucket="3_10"} 48
telemt_desync_frames_bucket_total{bucket="gt_10"} 48
telemt_pool_swap_total 2
telemt_pool_force_close_total 78
telemt_me_writer_removed_unexpected_total 2839
telemt_me_writer_restored_same_endpoint_total 2759
telemt_me_writer_removed_unexpected_minus_restored_total 80
telemt_user_connections_total{user="hello"} 93420
telemt_user_connections_current{user="hello"} 273
telemt_user_octets_from_client{user="hello"} 712161132 (679.17 MB)
telemt_user_octets_to_client{user="hello"} 28338099720 (26.39 GB)
telemt_user_unique_ips_current{user="hello"} 47
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 14202.9 (3h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 45437
telemt_connections_bad_total 104
telemt_handshake_timeouts_total 11053
telemt_upstream_connect_attempt_total 28338
telemt_upstream_connect_success_total 27979
telemt_upstream_connect_fail_total 163
telemt_upstream_connect_attempts_per_request{bucket="1"} 27973
telemt_upstream_connect_attempts_per_request{bucket="2"} 169
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18965
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8996
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 163
telemt_me_keepalive_timeout_total 642
telemt_me_reconnect_attempts_total 15996
telemt_me_reconnect_success_total 15987
telemt_me_reader_eof_total 16368
telemt_me_idle_close_by_peer_total 16367
telemt_me_route_drop_no_conn_total 16414
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 61
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 79
telemt_desync_full_logged_total 34
telemt_desync_suppressed_total 45
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 31
telemt_desync_frames_bucket_total{bucket="gt_10"} 36
telemt_me_writer_removed_unexpected_total 16429
telemt_me_writer_restored_same_endpoint_total 15967
telemt_me_writer_removed_unexpected_minus_restored_total 462
telemt_user_connections_total{user="hello"} 33756
telemt_user_connections_current{user="hello"} 97
telemt_user_octets_from_client{user="hello"} 227767916 (217.22 MB)
telemt_user_octets_to_client{user="hello"} 20085998220 (18.71 GB)
telemt_user_unique_ips_current{user="hello"} 16
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 14201.8 (3h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 105518
telemt_connections_bad_total 35567
telemt_handshake_timeouts_total 1943
telemt_upstream_connect_attempt_total 16278
telemt_upstream_connect_success_total 16189
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 16189
telemt_upstream_connect_attempts_per_request{bucket="2"} 40
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9401
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6730
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_keepalive_timeout_total 204
telemt_me_reconnect_attempts_total 5693
telemt_me_reconnect_success_total 5687
telemt_me_reader_eof_total 5920
telemt_me_idle_close_by_peer_total 5918
telemt_me_route_drop_no_conn_total 20809
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 61
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 225
telemt_desync_full_logged_total 74
telemt_desync_suppressed_total 151
telemt_desync_frames_bucket_total{bucket="1_2"} 46
telemt_desync_frames_bucket_total{bucket="3_10"} 84
telemt_desync_frames_bucket_total{bucket="gt_10"} 95
telemt_pool_swap_total 2
telemt_pool_force_close_total 61
telemt_me_writer_removed_unexpected_total 5921
telemt_me_writer_restored_same_endpoint_total 5666
telemt_me_writer_removed_unexpected_minus_restored_total 255
telemt_user_connections_total{user="hello"} 66702
telemt_user_connections_current{user="hello"} 128
telemt_user_octets_from_client{user="hello"} 407699540 (388.81 MB)
telemt_user_octets_to_client{user="hello"} 17117827976 (15.94 GB)
telemt_user_unique_ips_current{user="hello"} 27
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 14200.7 (3h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 46856
telemt_connections_bad_total 155
telemt_handshake_timeouts_total 529
telemt_upstream_connect_attempt_total 9061
telemt_upstream_connect_success_total 9026
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 9026
telemt_upstream_connect_attempts_per_request{bucket="2"} 17
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5555
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3470
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 94
telemt_me_reconnect_attempts_total 1310
telemt_me_reconnect_success_total 1321
telemt_me_reader_eof_total 1322
telemt_me_idle_close_by_peer_total 1322
telemt_me_route_drop_no_conn_total 16301
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 60
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 15
telemt_desync_full_logged_total 5
telemt_desync_suppressed_total 10
telemt_desync_frames_bucket_total{bucket="3_10"} 5
telemt_desync_frames_bucket_total{bucket="gt_10"} 10
telemt_pool_swap_total 4
telemt_pool_force_close_total 101
telemt_me_writer_removed_unexpected_total 1322
telemt_me_writer_restored_same_endpoint_total 1301
telemt_me_writer_removed_unexpected_minus_restored_total 21
telemt_user_connections_total{user="hello"} 45394
telemt_user_connections_current{user="hello"} 146
telemt_user_octets_from_client{user="hello"} 401976360 (383.35 MB)
telemt_user_octets_to_client{user="hello"} 11642435440 (10.84 GB)
telemt_user_unique_ips_current{user="hello"} 25
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 14199.4 (3h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 113963
telemt_connections_bad_total 52
telemt_handshake_timeouts_total 49235
telemt_upstream_connect_attempt_total 20834
telemt_upstream_connect_success_total 20709
telemt_upstream_connect_fail_total 59
telemt_upstream_connect_attempts_per_request{bucket="1"} 20709
telemt_upstream_connect_attempts_per_request{bucket="2"} 59
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11738
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8933
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 59
telemt_me_keepalive_timeout_total 276
telemt_me_reconnect_attempts_total 10611
telemt_me_reconnect_success_total 10612
telemt_me_reader_eof_total 11274
telemt_me_idle_close_by_peer_total 11273
telemt_me_route_drop_no_conn_total 37011
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 62
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 65
telemt_desync_full_logged_total 16
telemt_desync_suppressed_total 49
telemt_desync_frames_bucket_total{bucket="1_2"} 10
telemt_desync_frames_bucket_total{bucket="3_10"} 34
telemt_desync_frames_bucket_total{bucket="gt_10"} 21
telemt_pool_swap_total 1
telemt_pool_force_close_total 30
telemt_me_writer_removed_unexpected_total 11280
telemt_me_writer_restored_same_endpoint_total 10588
telemt_me_writer_removed_unexpected_minus_restored_total 692
telemt_user_connections_total{user="hello"} 62511
telemt_user_connections_current{user="hello"} 109
telemt_user_octets_from_client{user="hello"} 304887252 (290.76 MB)
telemt_user_octets_to_client{user="hello"} 15300688048 (14.25 GB)
telemt_user_unique_ips_current{user="hello"} 16
```