# Server Metrics 2026-03-14 12:07:38 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 194938.1 (54h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5646680
telemt_connections_bad_total 59026
telemt_handshake_timeouts_total 124291
telemt_upstream_connect_attempt_total 40840
telemt_upstream_connect_success_total 40579
telemt_upstream_connect_fail_total 261
telemt_upstream_connect_attempts_per_request{bucket="1"} 40840
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21970
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18450
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 159
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 261
telemt_me_keepalive_timeout_total 7844
telemt_me_reconnect_attempts_total 44920
telemt_me_reconnect_success_total 28547
telemt_me_reader_eof_total 30724
telemt_me_idle_close_by_peer_total 30723
telemt_me_route_drop_no_conn_total 2137963
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5180557
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 19998
telemt_desync_full_logged_total 5469
telemt_desync_suppressed_total 14529
telemt_desync_frames_bucket_total{bucket="1_2"} 4839
telemt_desync_frames_bucket_total{bucket="3_10"} 7620
telemt_desync_frames_bucket_total{bucket="gt_10"} 7539
telemt_pool_swap_total 164
telemt_me_writer_removed_unexpected_total 29473
telemt_me_refill_failed_total 506
telemt_me_writer_restored_same_endpoint_total 28534
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 926
telemt_user_connections_total{user="hello"} 5182091
telemt_user_connections_current{user="hello"} 1863
telemt_user_octets_from_client{user="hello"} 80429035832 (74.91 GB)
telemt_user_octets_to_client{user="hello"} 1648394357513 (1.50 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 489
telemt_user_unique_ips_recent_window{user="hello"} 245
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 94602.1 (26h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1087362
telemt_connections_bad_total 58933
telemt_handshake_timeouts_total 25139
telemt_upstream_connect_attempt_total 24477
telemt_upstream_connect_success_total 24172
telemt_upstream_connect_fail_total 304
telemt_upstream_connect_attempts_per_request{bucket="1"} 24476
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13157
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10703
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 48
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 264
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 304
telemt_me_keepalive_timeout_total 2401
telemt_me_reconnect_attempts_total 33798
telemt_me_reconnect_success_total 17420
telemt_me_reader_eof_total 18823
telemt_me_idle_close_by_peer_total 18822
telemt_me_route_drop_no_conn_total 367365
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 895541
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2474
telemt_desync_full_logged_total 778
telemt_desync_suppressed_total 1696
telemt_desync_frames_bucket_total{bucket="1_2"} 638
telemt_desync_frames_bucket_total{bucket="3_10"} 1025
telemt_desync_frames_bucket_total{bucket="gt_10"} 811
telemt_pool_swap_total 73
telemt_me_writer_removed_unexpected_total 18178
telemt_me_refill_failed_total 505
telemt_me_writer_restored_same_endpoint_total 17412
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 758
telemt_user_connections_total{user="hello"} 897452
telemt_user_connections_current{user="hello"} 753
telemt_user_octets_from_client{user="hello"} 9808531697 (9.13 GB)
telemt_user_octets_to_client{user="hello"} 317093515712 (295.32 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 194
telemt_user_unique_ips_recent_window{user="hello"} 97
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 224558.6 (62h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4005602
telemt_connections_bad_total 46209
telemt_handshake_timeouts_total 273261
telemt_upstream_connect_attempt_total 50594
telemt_upstream_connect_success_total 50573
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 50594
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26684
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23623
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 259
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 11269
telemt_me_reconnect_attempts_total 45068
telemt_me_reconnect_success_total 39067
telemt_me_reader_eof_total 41498
telemt_me_idle_close_by_peer_total 41496
telemt_me_route_drop_no_conn_total 1376535
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3350542
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10760
telemt_desync_full_logged_total 3634
telemt_desync_suppressed_total 7126
telemt_desync_frames_bucket_total{bucket="1_2"} 1958
telemt_desync_frames_bucket_total{bucket="3_10"} 3890
telemt_desync_frames_bucket_total{bucket="gt_10"} 4912
telemt_pool_swap_total 208
telemt_pool_stale_pick_total 5
telemt_me_writer_removed_unexpected_total 39644
telemt_me_refill_failed_total 180
telemt_me_writer_restored_same_endpoint_total 39026
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 577
telemt_user_connections_total{user="hello"} 3349691
telemt_user_connections_current{user="hello"} 988
telemt_user_octets_from_client{user="hello"} 57264509788 (53.33 GB)
telemt_user_octets_to_client{user="hello"} 1196693498981 (1.09 TB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 303
telemt_user_unique_ips_recent_window{user="hello"} 157
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 224561.2 (62h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2619298
telemt_connections_bad_total 23510
telemt_handshake_timeouts_total 337447
telemt_upstream_connect_attempt_total 69318
telemt_upstream_connect_success_total 66809
telemt_upstream_connect_fail_total 2371
telemt_upstream_connect_attempts_per_request{bucket="1"} 69043
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39776
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26867
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2370
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20961
telemt_me_reconnect_attempts_total 61380
telemt_me_reconnect_success_total 48596
telemt_me_reader_eof_total 52063
telemt_me_idle_close_by_peer_total 52055
telemt_me_route_drop_no_conn_total 870571
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2047802
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4117
telemt_desync_full_logged_total 1355
telemt_desync_suppressed_total 2762
telemt_desync_frames_bucket_total{bucket="1_2"} 1171
telemt_desync_frames_bucket_total{bucket="3_10"} 1683
telemt_desync_frames_bucket_total{bucket="gt_10"} 1263
telemt_pool_swap_total 192
telemt_me_writer_removed_unexpected_total 49421
telemt_me_refill_failed_total 389
telemt_me_writer_restored_same_endpoint_total 48571
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 825
telemt_user_connections_total{user="hello"} 2054221
telemt_user_connections_current{user="hello"} 475
telemt_user_octets_from_client{user="hello"} 30415722011 (28.33 GB)
telemt_user_octets_to_client{user="hello"} 732238724754 (681.95 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 143
telemt_user_unique_ips_recent_window{user="hello"} 81
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 93994.4 (26h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1073215
telemt_connections_bad_total 18117
telemt_handshake_timeouts_total 13849
telemt_upstream_connect_attempt_total 22843
telemt_upstream_connect_success_total 22204
telemt_upstream_connect_fail_total 639
telemt_upstream_connect_attempts_per_request{bucket="1"} 22843
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10647
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11531
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 639
telemt_me_keepalive_timeout_total 1791
telemt_me_reconnect_attempts_total 83924
telemt_me_reconnect_success_total 17510
telemt_me_reader_eof_total 19993
telemt_me_idle_close_by_peer_total 19992
telemt_me_route_drop_no_conn_total 434200
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 993976
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2659
telemt_desync_full_logged_total 834
telemt_desync_suppressed_total 1825
telemt_desync_frames_bucket_total{bucket="1_2"} 962
telemt_desync_frames_bucket_total{bucket="3_10"} 941
telemt_desync_frames_bucket_total{bucket="gt_10"} 756
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 19744
telemt_me_refill_failed_total 2070
telemt_me_writer_restored_same_endpoint_total 17505
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 2234
telemt_user_connections_total{user="hello"} 993180
telemt_user_connections_current{user="hello"} 744
telemt_user_octets_from_client{user="hello"} 17191963276 (16.01 GB)
telemt_user_octets_to_client{user="hello"} 334686085008 (311.70 GB)
telemt_user_unique_ips_current{user="hello"} 196
telemt_user_unique_ips_recent_window{user="hello"} 93
```