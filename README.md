# Server Metrics 2026-03-11 19:42:31 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 105325.0 (29h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2673799
telemt_connections_bad_total 48666
telemt_handshake_timeouts_total 59233
telemt_upstream_connect_attempt_total 22160
telemt_upstream_connect_success_total 22148
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 22160
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11192
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10846
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 5393
telemt_me_reconnect_attempts_total 34724
telemt_me_reconnect_success_total 16831
telemt_me_reader_eof_total 18189
telemt_me_idle_close_by_peer_total 18189
telemt_me_route_drop_no_conn_total 1010230
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2443070
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 12382
telemt_desync_full_logged_total 3434
telemt_desync_suppressed_total 8948
telemt_desync_frames_bucket_total{bucket="1_2"} 3043
telemt_desync_frames_bucket_total{bucket="3_10"} 4778
telemt_desync_frames_bucket_total{bucket="gt_10"} 4561
telemt_pool_swap_total 75
telemt_me_writer_removed_unexpected_total 17582
telemt_me_refill_failed_total 555
telemt_me_writer_restored_same_endpoint_total 16825
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 751
telemt_user_connections_total{user="hello"} 2441421
telemt_user_connections_current{user="hello"} 1163
telemt_user_octets_from_client{user="hello"} 36439397520 (33.94 GB)
telemt_user_octets_to_client{user="hello"} 693080957076 (645.48 GB)
telemt_user_unique_ips_current{user="hello"} 320
telemt_user_unique_ips_recent_window{user="hello"} 137
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 105381.7 (29h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 993871
telemt_connections_bad_total 16481
telemt_handshake_timeouts_total 89680
telemt_upstream_connect_attempt_total 32392
telemt_upstream_connect_success_total 29420
telemt_upstream_connect_fail_total 2971
telemt_upstream_connect_attempts_per_request{bucket="1"} 32391
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13893
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13256
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2062
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2971
telemt_me_keepalive_timeout_total 2856
telemt_me_reconnect_attempts_total 23290
telemt_me_reconnect_success_total 21172
telemt_me_reader_eof_total 22423
telemt_me_idle_close_by_peer_total 22420
telemt_me_route_drop_no_conn_total 375505
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 829153
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3306
telemt_desync_full_logged_total 1070
telemt_desync_suppressed_total 2236
telemt_desync_frames_bucket_total{bucket="1_2"} 1053
telemt_desync_frames_bucket_total{bucket="3_10"} 1176
telemt_desync_frames_bucket_total{bucket="gt_10"} 1077
telemt_pool_swap_total 85
telemt_me_writer_removed_unexpected_total 21478
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 21149
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 306
telemt_user_connections_total{user="hello"} 831599
telemt_user_connections_current{user="hello"} 377
telemt_user_octets_from_client{user="hello"} 9994276850 (9.31 GB)
telemt_user_octets_to_client{user="hello"} 241405859704 (224.83 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 121
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 105381.7 (29h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1714499
telemt_connections_bad_total 10660
telemt_handshake_timeouts_total 134338
telemt_upstream_connect_attempt_total 27088
telemt_upstream_connect_success_total 26749
telemt_upstream_connect_fail_total 339
telemt_upstream_connect_attempts_per_request{bucket="1"} 27088
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14472
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12139
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 137
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 339
telemt_me_keepalive_timeout_total 2004
telemt_me_reconnect_attempts_total 52718
telemt_me_reconnect_success_total 20343
telemt_me_reader_eof_total 22213
telemt_me_idle_close_by_peer_total 22213
telemt_me_route_drop_no_conn_total 624536
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1504946
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4113
telemt_desync_full_logged_total 1212
telemt_desync_suppressed_total 2901
telemt_desync_frames_bucket_total{bucket="1_2"} 961
telemt_desync_frames_bucket_total{bucket="3_10"} 1560
telemt_desync_frames_bucket_total{bucket="gt_10"} 1592
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 21634
telemt_me_refill_failed_total 1006
telemt_me_writer_restored_same_endpoint_total 20331
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 1291
telemt_user_connections_total{user="hello"} 1504590
telemt_user_connections_current{user="hello"} 690
telemt_user_octets_from_client{user="hello"} 19371412057 (18.04 GB)
telemt_user_octets_to_client{user="hello"} 458729190505 (427.22 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 205
telemt_user_unique_ips_recent_window{user="hello"} 87
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 105382.2 (29h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1224880
telemt_connections_bad_total 78201
telemt_handshake_timeouts_total 110883
telemt_upstream_connect_attempt_total 28451
telemt_upstream_connect_success_total 28451
telemt_upstream_connect_attempts_per_request{bucket="1"} 28451
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15514
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12931
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1471
telemt_me_reconnect_attempts_total 27782
telemt_me_reconnect_success_total 23167
telemt_me_reader_eof_total 24591
telemt_me_idle_close_by_peer_total 24590
telemt_me_seq_mismatch_total 23
telemt_me_route_drop_no_conn_total 409582
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1000507
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 34
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2139
telemt_desync_full_logged_total 804
telemt_desync_suppressed_total 1335
telemt_desync_frames_bucket_total{bucket="1_2"} 765
telemt_desync_frames_bucket_total{bucket="3_10"} 725
telemt_desync_frames_bucket_total{bucket="gt_10"} 649
telemt_pool_swap_total 85
telemt_me_writer_removed_unexpected_total 23552
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 23134
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 385
telemt_user_connections_total{user="hello"} 999719
telemt_user_connections_current{user="hello"} 434
telemt_user_octets_from_client{user="hello"} 11908235720 (11.09 GB)
telemt_user_octets_to_client{user="hello"} 306361335112 (285.32 GB)
telemt_user_unique_ips_current{user="hello"} 131
telemt_user_unique_ips_recent_window{user="hello"} 69
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 10058.2 (2h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 158000
telemt_connections_bad_total 2273
telemt_handshake_timeouts_total 1174
telemt_upstream_connect_attempt_total 2942
telemt_upstream_connect_success_total 2941
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 2942
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1536
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1389
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 61
telemt_me_reconnect_attempts_total 2386
telemt_me_reconnect_success_total 2364
telemt_me_reader_eof_total 2431
telemt_me_idle_close_by_peer_total 2431
telemt_me_seq_mismatch_total 3
telemt_me_route_drop_no_conn_total 53479
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 142024
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 25
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 311
telemt_desync_full_logged_total 98
telemt_desync_suppressed_total 213
telemt_desync_frames_bucket_total{bucket="1_2"} 73
telemt_desync_frames_bucket_total{bucket="3_10"} 106
telemt_desync_frames_bucket_total{bucket="gt_10"} 132
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 2391
telemt_me_writer_restored_same_endpoint_total 2339
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 256
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 141990
telemt_user_connections_current{user="hello"} 513
telemt_user_octets_from_client{user="hello"} 9278427820 (8.64 GB)
telemt_user_octets_to_client{user="hello"} 47890865624 (44.60 GB)
telemt_user_unique_ips_current{user="hello"} 150
telemt_user_unique_ips_recent_window{user="hello"} 73
```