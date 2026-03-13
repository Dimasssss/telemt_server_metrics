# Server Metrics 2026-03-13 14:04:04 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 115526.2 (32h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3512796
telemt_connections_bad_total 37397
telemt_handshake_timeouts_total 60052
telemt_upstream_connect_attempt_total 22634
telemt_upstream_connect_success_total 22508
telemt_upstream_connect_fail_total 126
telemt_upstream_connect_attempts_per_request{bucket="1"} 22634
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11618
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10831
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 126
telemt_me_keepalive_timeout_total 2144
telemt_me_reconnect_attempts_total 26837
telemt_me_reconnect_success_total 16753
telemt_me_reader_eof_total 18011
telemt_me_idle_close_by_peer_total 18010
telemt_me_route_drop_no_conn_total 1303670
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3225175
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 13362
telemt_desync_full_logged_total 3495
telemt_desync_suppressed_total 9867
telemt_desync_frames_bucket_total{bucket="1_2"} 3403
telemt_desync_frames_bucket_total{bucket="3_10"} 5053
telemt_desync_frames_bucket_total{bucket="gt_10"} 4906
telemt_pool_swap_total 95
telemt_me_writer_removed_unexpected_total 17301
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 16740
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 548
telemt_user_connections_total{user="hello"} 3225039
telemt_user_connections_current{user="hello"} 1760
telemt_user_octets_from_client{user="hello"} 44490624924 (41.44 GB)
telemt_user_octets_to_client{user="hello"} 1025784232236 (955.34 GB)
telemt_user_unique_ips_current{user="hello"} 470
telemt_user_unique_ips_recent_window{user="hello"} 246
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 15190.1 (4h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 211947
telemt_connections_bad_total 12089
telemt_handshake_timeouts_total 5383
telemt_upstream_connect_attempt_total 3737
telemt_upstream_connect_success_total 3660
telemt_upstream_connect_fail_total 77
telemt_upstream_connect_attempts_per_request{bucket="1"} 3737
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1876
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1747
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 77
telemt_me_keepalive_timeout_total 73
telemt_me_reconnect_attempts_total 4097
telemt_me_reconnect_success_total 2865
telemt_me_reader_eof_total 2996
telemt_me_idle_close_by_peer_total 2996
telemt_me_route_drop_no_conn_total 76998
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 188959
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 736
telemt_desync_full_logged_total 175
telemt_desync_suppressed_total 561
telemt_desync_frames_bucket_total{bucket="1_2"} 136
telemt_desync_frames_bucket_total{bucket="3_10"} 374
telemt_desync_frames_bucket_total{bucket="gt_10"} 226
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 2927
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 2858
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 62
telemt_user_connections_total{user="hello"} 188983
telemt_user_connections_current{user="hello"} 706
telemt_user_octets_from_client{user="hello"} 1937584656 (1.80 GB)
telemt_user_octets_to_client{user="hello"} 53470014612 (49.80 GB)
telemt_user_unique_ips_current{user="hello"} 199
telemt_user_unique_ips_recent_window{user="hello"} 111
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 145146.9 (40h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2635502
telemt_connections_bad_total 27068
telemt_handshake_timeouts_total 176734
telemt_upstream_connect_attempt_total 32800
telemt_upstream_connect_success_total 32790
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 32800
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17069
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15595
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 121
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 3207
telemt_me_reconnect_attempts_total 27760
telemt_me_reconnect_success_total 25214
telemt_me_reader_eof_total 26736
telemt_me_idle_close_by_peer_total 26735
telemt_me_route_drop_no_conn_total 885410
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2150240
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7598
telemt_desync_full_logged_total 2485
telemt_desync_suppressed_total 5113
telemt_desync_frames_bucket_total{bucket="1_2"} 1193
telemt_desync_frames_bucket_total{bucket="3_10"} 2764
telemt_desync_frames_bucket_total{bucket="gt_10"} 3641
telemt_pool_swap_total 136
telemt_me_writer_removed_unexpected_total 25508
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 25173
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 294
telemt_user_connections_total{user="hello"} 2149653
telemt_user_connections_current{user="hello"} 1110
telemt_user_octets_from_client{user="hello"} 35899914864 (33.43 GB)
telemt_user_octets_to_client{user="hello"} 764917583005 (712.39 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 324
telemt_user_unique_ips_recent_window{user="hello"} 180
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 145147.3 (40h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1680542
telemt_connections_bad_total 18056
telemt_handshake_timeouts_total 120939
telemt_upstream_connect_attempt_total 46211
telemt_upstream_connect_success_total 43889
telemt_upstream_connect_fail_total 2185
telemt_upstream_connect_attempts_per_request{bucket="1"} 45937
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26443
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17355
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2184
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 11840
telemt_me_reconnect_attempts_total 39766
telemt_me_reconnect_success_total 30799
telemt_me_reader_eof_total 33117
telemt_me_idle_close_by_peer_total 33110
telemt_me_route_drop_no_conn_total 599250
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1405114
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2813
telemt_desync_full_logged_total 913
telemt_desync_suppressed_total 1900
telemt_desync_frames_bucket_total{bucket="1_2"} 749
telemt_desync_frames_bucket_total{bucket="3_10"} 1171
telemt_desync_frames_bucket_total{bucket="gt_10"} 893
telemt_pool_swap_total 127
telemt_me_writer_removed_unexpected_total 31309
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 30775
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 510
telemt_user_connections_total{user="hello"} 1409830
telemt_user_connections_current{user="hello"} 635
telemt_user_octets_from_client{user="hello"} 21713212465 (20.22 GB)
telemt_user_octets_to_client{user="hello"} 544882850278 (507.46 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 198
telemt_user_unique_ips_recent_window{user="hello"} 107
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 14583.4 (4h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 229456
telemt_connections_bad_total 3860
telemt_handshake_timeouts_total 2137
telemt_upstream_connect_attempt_total 3041
telemt_upstream_connect_success_total 2937
telemt_upstream_connect_fail_total 104
telemt_upstream_connect_attempts_per_request{bucket="1"} 3041
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1412
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1521
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 104
telemt_me_keepalive_timeout_total 45
telemt_me_reconnect_attempts_total 10230
telemt_me_reconnect_success_total 2154
telemt_me_reader_eof_total 2430
telemt_me_idle_close_by_peer_total 2430
telemt_me_route_drop_no_conn_total 89620
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 214494
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 748
telemt_desync_full_logged_total 236
telemt_desync_suppressed_total 512
telemt_desync_frames_bucket_total{bucket="1_2"} 293
telemt_desync_frames_bucket_total{bucket="3_10"} 290
telemt_desync_frames_bucket_total{bucket="gt_10"} 165
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 2408
telemt_me_refill_failed_total 251
telemt_me_writer_restored_same_endpoint_total 2150
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 254
telemt_user_connections_total{user="hello"} 214476
telemt_user_connections_current{user="hello"} 824
telemt_user_octets_from_client{user="hello"} 2336634520 (2.18 GB)
telemt_user_octets_to_client{user="hello"} 66981470380 (62.38 GB)
telemt_user_unique_ips_current{user="hello"} 212
telemt_user_unique_ips_recent_window{user="hello"} 102
```