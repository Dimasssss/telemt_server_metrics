# Server Metrics 2026-03-13 02:39:35 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 74454.4 (20h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2095544
telemt_connections_bad_total 27822
telemt_handshake_timeouts_total 22263
telemt_upstream_connect_attempt_total 14735
telemt_upstream_connect_success_total 14652
telemt_upstream_connect_fail_total 83
telemt_upstream_connect_attempts_per_request{bucket="1"} 14735
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7542
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7066
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 83
telemt_me_keepalive_timeout_total 1265
telemt_me_reconnect_attempts_total 19800
telemt_me_reconnect_success_total 10939
telemt_me_reader_eof_total 11816
telemt_me_idle_close_by_peer_total 11815
telemt_me_route_drop_no_conn_total 808088
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1932804
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8706
telemt_desync_full_logged_total 2268
telemt_desync_suppressed_total 6438
telemt_desync_frames_bucket_total{bucket="1_2"} 2297
telemt_desync_frames_bucket_total{bucket="3_10"} 3139
telemt_desync_frames_bucket_total{bucket="gt_10"} 3270
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 11369
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 10926
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 430
telemt_user_connections_total{user="hello"} 1932261
telemt_user_connections_current{user="hello"} 647
telemt_user_octets_from_client{user="hello"} 28140170312 (26.21 GB)
telemt_user_octets_to_client{user="hello"} 671635983288 (625.51 GB)
telemt_user_unique_ips_current{user="hello"} 231
telemt_user_unique_ips_recent_window{user="hello"} 72
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 104074.9 (28h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 855416
telemt_connections_bad_total 11818
telemt_handshake_timeouts_total 32388
telemt_upstream_connect_attempt_total 26514
telemt_upstream_connect_success_total 26485
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 26514
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13743
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12652
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3456
telemt_me_reconnect_attempts_total 19767
telemt_me_reconnect_success_total 19659
telemt_me_reader_eof_total 20945
telemt_me_idle_close_by_peer_total 20945
telemt_me_route_drop_no_conn_total 275183
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 775954
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3100
telemt_desync_full_logged_total 974
telemt_desync_suppressed_total 2126
telemt_desync_frames_bucket_total{bucket="1_2"} 1257
telemt_desync_frames_bucket_total{bucket="3_10"} 1006
telemt_desync_frames_bucket_total{bucket="gt_10"} 837
telemt_pool_swap_total 106
telemt_me_writer_removed_unexpected_total 19851
telemt_me_writer_restored_same_endpoint_total 19650
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 192
telemt_user_connections_total{user="hello"} 777857
telemt_user_connections_current{user="hello"} 206
telemt_user_octets_from_client{user="hello"} 12377821652 (11.53 GB)
telemt_user_octets_to_client{user="hello"} 292847367147 (272.74 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 85
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 104074.8 (28h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1774922
telemt_connections_bad_total 9185
telemt_handshake_timeouts_total 118603
telemt_upstream_connect_attempt_total 24290
telemt_upstream_connect_success_total 24280
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 24290
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12773
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11412
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1606
telemt_me_reconnect_attempts_total 20007
telemt_me_reconnect_success_total 18744
telemt_me_reader_eof_total 19850
telemt_me_idle_close_by_peer_total 19849
telemt_me_route_drop_no_conn_total 578651
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1397820
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5022
telemt_desync_full_logged_total 1538
telemt_desync_suppressed_total 3484
telemt_desync_frames_bucket_total{bucket="1_2"} 804
telemt_desync_frames_bucket_total{bucket="3_10"} 1818
telemt_desync_frames_bucket_total{bucket="gt_10"} 2400
telemt_pool_swap_total 97
telemt_me_writer_removed_unexpected_total 18918
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 18703
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 174
telemt_user_connections_total{user="hello"} 1397415
telemt_user_connections_current{user="hello"} 330
telemt_user_octets_from_client{user="hello"} 20215980884 (18.83 GB)
telemt_user_octets_to_client{user="hello"} 503464092733 (468.89 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 129
telemt_user_unique_ips_recent_window{user="hello"} 53
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 104075.1 (28h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1108546
telemt_connections_bad_total 13138
telemt_handshake_timeouts_total 73302
telemt_upstream_connect_attempt_total 36384
telemt_upstream_connect_success_total 34110
telemt_upstream_connect_fail_total 2136
telemt_upstream_connect_attempts_per_request{bucket="1"} 36109
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21135
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12884
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2135
telemt_me_keepalive_timeout_total 11362
telemt_me_reconnect_attempts_total 31986
telemt_me_reconnect_success_total 23060
telemt_me_reader_eof_total 24905
telemt_me_idle_close_by_peer_total 24898
telemt_me_route_drop_no_conn_total 392933
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 950657
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1896
telemt_desync_full_logged_total 629
telemt_desync_suppressed_total 1267
telemt_desync_frames_bucket_total{bucket="1_2"} 523
telemt_desync_frames_bucket_total{bucket="3_10"} 743
telemt_desync_frames_bucket_total{bucket="gt_10"} 630
telemt_pool_swap_total 88
telemt_me_writer_removed_unexpected_total 23491
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 23036
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 431
telemt_user_connections_total{user="hello"} 955828
telemt_user_connections_current{user="hello"} 254
telemt_user_octets_from_client{user="hello"} 14586134745 (13.58 GB)
telemt_user_octets_to_client{user="hello"} 375322775626 (349.55 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 98
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 104074.8 (28h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1225679
telemt_connections_bad_total 12629
telemt_handshake_timeouts_total 9551
telemt_upstream_connect_attempt_total 32959
telemt_upstream_connect_success_total 32556
telemt_upstream_connect_fail_total 403
telemt_upstream_connect_attempts_per_request{bucket="1"} 32959
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16689
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15687
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 167
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 403
telemt_me_keepalive_timeout_total 1895
telemt_me_reconnect_attempts_total 41102
telemt_me_reconnect_success_total 27372
telemt_me_reader_eof_total 28801
telemt_me_idle_close_by_peer_total 28801
telemt_me_seq_mismatch_total 37
telemt_me_route_drop_no_conn_total 457939
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1133454
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 41
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4213
telemt_desync_full_logged_total 1494
telemt_desync_suppressed_total 2719
telemt_desync_frames_bucket_total{bucket="1_2"} 1266
telemt_desync_frames_bucket_total{bucket="3_10"} 1391
telemt_desync_frames_bucket_total{bucket="gt_10"} 1556
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 28114
telemt_me_refill_failed_total 425
telemt_me_writer_restored_same_endpoint_total 27323
telemt_me_writer_restored_fallback_total 49
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 742
telemt_user_connections_total{user="hello"} 1133309
telemt_user_connections_current{user="hello"} 353
telemt_user_octets_from_client{user="hello"} 14007101348 (13.05 GB)
telemt_user_octets_to_client{user="hello"} 392366541392 (365.42 GB)
telemt_user_unique_ips_current{user="hello"} 110
telemt_user_unique_ips_recent_window{user="hello"} 42
```