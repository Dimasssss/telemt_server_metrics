# Server Metrics 2026-03-13 16:57:42 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 125944.9 (34h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4004393
telemt_connections_bad_total 37515
telemt_handshake_timeouts_total 99985
telemt_upstream_connect_attempt_total 26795
telemt_upstream_connect_success_total 26619
telemt_upstream_connect_fail_total 176
telemt_upstream_connect_attempts_per_request{bucket="1"} 26795
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14754
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11750
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 115
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 176
telemt_me_keepalive_timeout_total 4001
telemt_me_reconnect_attempts_total 28107
telemt_me_reconnect_success_total 18003
telemt_me_reader_eof_total 19340
telemt_me_idle_close_by_peer_total 19339
telemt_me_route_drop_no_conn_total 1485406
telemt_me_route_drop_channel_closed_total 20
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3655805
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 14359
telemt_desync_full_logged_total 3792
telemt_desync_suppressed_total 10567
telemt_desync_frames_bucket_total{bucket="1_2"} 3582
telemt_desync_frames_bucket_total{bucket="3_10"} 5437
telemt_desync_frames_bucket_total{bucket="gt_10"} 5340
telemt_pool_swap_total 105
telemt_me_writer_removed_unexpected_total 18568
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 17990
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 565
telemt_user_connections_total{user="hello"} 3657975
telemt_user_connections_current{user="hello"} 1556
telemt_user_octets_from_client{user="hello"} 51512600452 (47.97 GB)
telemt_user_octets_to_client{user="hello"} 1140181645425 (1.04 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 415
telemt_user_unique_ips_recent_window{user="hello"} 199
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 25608.8 (7h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 381806
telemt_connections_bad_total 27753
telemt_handshake_timeouts_total 10196
telemt_upstream_connect_attempt_total 7570
telemt_upstream_connect_success_total 7405
telemt_upstream_connect_fail_total 164
telemt_upstream_connect_attempts_per_request{bucket="1"} 7569
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4282
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2994
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 18
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 111
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 164
telemt_me_keepalive_timeout_total 1130
telemt_me_reconnect_attempts_total 8055
telemt_me_reconnect_success_total 4667
telemt_me_reader_eof_total 4941
telemt_me_idle_close_by_peer_total 4940
telemt_me_route_drop_no_conn_total 137150
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 332898
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1177
telemt_desync_full_logged_total 306
telemt_desync_suppressed_total 871
telemt_desync_frames_bucket_total{bucket="1_2"} 230
telemt_desync_frames_bucket_total{bucket="3_10"} 562
telemt_desync_frames_bucket_total{bucket="gt_10"} 385
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 4826
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 4660
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 159
telemt_user_connections_total{user="hello"} 334322
telemt_user_connections_current{user="hello"} 456
telemt_user_octets_from_client{user="hello"} 3307479995 (3.08 GB)
telemt_user_octets_to_client{user="hello"} 96681493676 (90.04 GB)
telemt_user_msgs_from_client{user="hello"} 4402
telemt_user_msgs_to_client{user="hello"} 9145
telemt_user_unique_ips_current{user="hello"} 142
telemt_user_unique_ips_recent_window{user="hello"} 176
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 155565.4 (43h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2931539
telemt_connections_bad_total 28319
telemt_handshake_timeouts_total 196540
telemt_upstream_connect_attempt_total 34748
telemt_upstream_connect_success_total 34738
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 34748
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17964
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16643
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 126
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 3346
telemt_me_reconnect_attempts_total 29229
telemt_me_reconnect_success_total 26675
telemt_me_reader_eof_total 28285
telemt_me_idle_close_by_peer_total 28284
telemt_me_route_drop_no_conn_total 996359
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2416637
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8422
telemt_desync_full_logged_total 2785
telemt_desync_suppressed_total 5637
telemt_desync_frames_bucket_total{bucket="1_2"} 1357
telemt_desync_frames_bucket_total{bucket="3_10"} 3080
telemt_desync_frames_bucket_total{bucket="gt_10"} 3985
telemt_pool_swap_total 146
telemt_me_writer_removed_unexpected_total 26987
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 26634
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 312
telemt_user_connections_total{user="hello"} 2416003
telemt_user_connections_current{user="hello"} 1266
telemt_user_octets_from_client{user="hello"} 39346250080 (36.64 GB)
telemt_user_octets_to_client{user="hello"} 843277428797 (785.36 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 325
telemt_user_unique_ips_recent_window{user="hello"} 156
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 155565.9 (43h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1889016
telemt_connections_bad_total 18219
telemt_handshake_timeouts_total 172354
telemt_upstream_connect_attempt_total 48599
telemt_upstream_connect_success_total 46263
telemt_upstream_connect_fail_total 2199
telemt_upstream_connect_attempts_per_request{bucket="1"} 48325
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27718
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18454
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2198
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 11924
telemt_me_reconnect_attempts_total 41659
telemt_me_reconnect_success_total 32679
telemt_me_reader_eof_total 35099
telemt_me_idle_close_by_peer_total 35092
telemt_me_route_drop_no_conn_total 671115
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1557279
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3111
telemt_desync_full_logged_total 1009
telemt_desync_suppressed_total 2102
telemt_desync_frames_bucket_total{bucket="1_2"} 859
telemt_desync_frames_bucket_total{bucket="3_10"} 1281
telemt_desync_frames_bucket_total{bucket="gt_10"} 971
telemt_pool_swap_total 135
telemt_me_writer_removed_unexpected_total 33217
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 32655
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 538
telemt_user_connections_total{user="hello"} 1561975
telemt_user_connections_current{user="hello"} 736
telemt_user_octets_from_client{user="hello"} 24172591473 (22.51 GB)
telemt_user_octets_to_client{user="hello"} 592704299330 (552.00 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 201
telemt_user_unique_ips_recent_window{user="hello"} 112
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 25001.2 (6h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 407722
telemt_connections_bad_total 4213
telemt_handshake_timeouts_total 3929
telemt_upstream_connect_attempt_total 5655
telemt_upstream_connect_success_total 5481
telemt_upstream_connect_fail_total 174
telemt_upstream_connect_attempts_per_request{bucket="1"} 5655
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2506
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2970
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 174
telemt_me_keepalive_timeout_total 374
telemt_me_reconnect_attempts_total 15922
telemt_me_reconnect_success_total 4212
telemt_me_reader_eof_total 4669
telemt_me_idle_close_by_peer_total 4669
telemt_me_route_drop_no_conn_total 157968
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 380966
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1235
telemt_desync_full_logged_total 391
telemt_desync_suppressed_total 844
telemt_desync_frames_bucket_total{bucket="1_2"} 408
telemt_desync_frames_bucket_total{bucket="3_10"} 496
telemt_desync_frames_bucket_total{bucket="gt_10"} 331
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 4609
telemt_me_refill_failed_total 364
telemt_me_writer_restored_same_endpoint_total 4208
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 397
telemt_user_connections_total{user="hello"} 380941
telemt_user_connections_current{user="hello"} 786
telemt_user_octets_from_client{user="hello"} 4392415772 (4.09 GB)
telemt_user_octets_to_client{user="hello"} 120352041504 (112.09 GB)
telemt_user_unique_ips_current{user="hello"} 206
telemt_user_unique_ips_recent_window{user="hello"} 98
```