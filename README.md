# Server Metrics 2026-03-14 08:17:20 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 181120.2 (50h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5126377
telemt_connections_bad_total 42611
telemt_handshake_timeouts_total 116210
telemt_upstream_connect_attempt_total 38128
telemt_upstream_connect_success_total 37879
telemt_upstream_connect_fail_total 249
telemt_upstream_connect_attempts_per_request{bucket="1"} 38128
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20548
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17180
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 151
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 249
telemt_me_keepalive_timeout_total 7413
telemt_me_reconnect_attempts_total 37736
telemt_me_reconnect_success_total 26526
telemt_me_reader_eof_total 28470
telemt_me_idle_close_by_peer_total 28469
telemt_me_route_drop_no_conn_total 1939900
telemt_me_route_drop_channel_closed_total 27
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4700838
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 17917
telemt_desync_full_logged_total 4879
telemt_desync_suppressed_total 13038
telemt_desync_frames_bucket_total{bucket="1_2"} 4463
telemt_desync_frames_bucket_total{bucket="3_10"} 6800
telemt_desync_frames_bucket_total{bucket="gt_10"} 6654
telemt_pool_swap_total 157
telemt_me_writer_removed_unexpected_total 27261
telemt_me_refill_failed_total 345
telemt_me_writer_restored_same_endpoint_total 26513
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 735
telemt_user_connections_total{user="hello"} 4702271
telemt_user_connections_current{user="hello"} 1607
telemt_user_octets_from_client{user="hello"} 72119279768 (67.17 GB)
telemt_user_octets_to_client{user="hello"} 1504534849049 (1.37 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 447
telemt_user_unique_ips_recent_window{user="hello"} 216
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 80784.1 (22h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 885996
telemt_connections_bad_total 53910
telemt_handshake_timeouts_total 16528
telemt_upstream_connect_attempt_total 21733
telemt_upstream_connect_success_total 21454
telemt_upstream_connect_fail_total 279
telemt_upstream_connect_attempts_per_request{bucket="1"} 21733
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11672
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9504
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 37
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 241
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 279
telemt_me_keepalive_timeout_total 2175
telemt_me_reconnect_attempts_total 18884
telemt_me_reconnect_success_total 15414
telemt_me_reader_eof_total 16368
telemt_me_idle_close_by_peer_total 16367
telemt_me_route_drop_no_conn_total 293831
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 714514
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2146
telemt_desync_full_logged_total 668
telemt_desync_suppressed_total 1478
telemt_desync_frames_bucket_total{bucket="1_2"} 471
telemt_desync_frames_bucket_total{bucket="3_10"} 931
telemt_desync_frames_bucket_total{bucket="gt_10"} 744
telemt_pool_swap_total 70
telemt_me_writer_removed_unexpected_total 15747
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 15406
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 333
telemt_user_connections_total{user="hello"} 716422
telemt_user_connections_current{user="hello"} 616
telemt_user_octets_from_client{user="hello"} 7538329789 (7.02 GB)
telemt_user_octets_to_client{user="hello"} 248886932852 (231.79 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 179
telemt_user_unique_ips_recent_window{user="hello"} 99
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 210740.9 (58h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3661692
telemt_connections_bad_total 43211
telemt_handshake_timeouts_total 240283
telemt_upstream_connect_attempt_total 47606
telemt_upstream_connect_success_total 47585
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 47606
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25125
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22207
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 246
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10764
telemt_me_reconnect_attempts_total 41756
telemt_me_reconnect_success_total 36773
telemt_me_reader_eof_total 39049
telemt_me_idle_close_by_peer_total 39048
telemt_me_route_drop_no_conn_total 1255290
telemt_me_route_drop_channel_closed_total 20
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3056628
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10017
telemt_desync_full_logged_total 3373
telemt_desync_suppressed_total 6644
telemt_desync_frames_bucket_total{bucket="1_2"} 1763
telemt_desync_frames_bucket_total{bucket="3_10"} 3623
telemt_desync_frames_bucket_total{bucket="gt_10"} 4631
telemt_pool_swap_total 199
telemt_me_writer_removed_unexpected_total 37283
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 36732
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 510
telemt_user_connections_total{user="hello"} 3055762
telemt_user_connections_current{user="hello"} 895
telemt_user_octets_from_client{user="hello"} 51843503392 (48.28 GB)
telemt_user_octets_to_client{user="hello"} 1093932884001 (1018.80 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 275
telemt_user_unique_ips_recent_window{user="hello"} 145
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 210743.4 (58h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2433701
telemt_connections_bad_total 23335
telemt_handshake_timeouts_total 296168
telemt_upstream_connect_attempt_total 65504
telemt_upstream_connect_success_total 63007
telemt_upstream_connect_fail_total 2360
telemt_upstream_connect_attempts_per_request{bucket="1"} 65230
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37607
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25234
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2359
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20572
telemt_me_reconnect_attempts_total 54569
telemt_me_reconnect_success_total 45486
telemt_me_reader_eof_total 48738
telemt_me_idle_close_by_peer_total 48731
telemt_me_route_drop_no_conn_total 816770
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1914196
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3941
telemt_desync_full_logged_total 1286
telemt_desync_suppressed_total 2655
telemt_desync_frames_bucket_total{bucket="1_2"} 1090
telemt_desync_frames_bucket_total{bucket="3_10"} 1618
telemt_desync_frames_bucket_total{bucket="gt_10"} 1233
telemt_pool_swap_total 186
telemt_me_writer_removed_unexpected_total 46162
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 45462
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 676
telemt_user_connections_total{user="hello"} 1920320
telemt_user_connections_current{user="hello"} 455
telemt_user_octets_from_client{user="hello"} 28727520719 (26.75 GB)
telemt_user_octets_to_client{user="hello"} 699283523826 (651.26 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 128
telemt_user_unique_ips_recent_window{user="hello"} 77
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 80176.7 (22h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 866122
telemt_connections_bad_total 9585
telemt_handshake_timeouts_total 10257
telemt_upstream_connect_attempt_total 20285
telemt_upstream_connect_success_total 19742
telemt_upstream_connect_fail_total 543
telemt_upstream_connect_attempts_per_request{bucket="1"} 20285
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9455
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10261
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 543
telemt_me_keepalive_timeout_total 1624
telemt_me_reconnect_attempts_total 66276
telemt_me_reconnect_success_total 15746
telemt_me_reader_eof_total 17699
telemt_me_idle_close_by_peer_total 17698
telemt_me_route_drop_no_conn_total 331934
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 807860
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2061
telemt_desync_full_logged_total 650
telemt_desync_suppressed_total 1411
telemt_desync_frames_bucket_total{bucket="1_2"} 657
telemt_desync_frames_bucket_total{bucket="3_10"} 779
telemt_desync_frames_bucket_total{bucket="gt_10"} 625
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 17461
telemt_me_refill_failed_total 1574
telemt_me_writer_restored_same_endpoint_total 15741
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1715
telemt_user_connections_total{user="hello"} 807717
telemt_user_connections_current{user="hello"} 761
telemt_user_octets_from_client{user="hello"} 14773255384 (13.76 GB)
telemt_user_octets_to_client{user="hello"} 270965867208 (252.36 GB)
telemt_user_unique_ips_current{user="hello"} 185
telemt_user_unique_ips_recent_window{user="hello"} 99
```