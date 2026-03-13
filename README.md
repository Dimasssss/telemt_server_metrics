# Server Metrics 2026-03-13 17:18:05 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 127167.9 (35h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4051252
telemt_connections_bad_total 37517
telemt_handshake_timeouts_total 100679
telemt_upstream_connect_attempt_total 27057
telemt_upstream_connect_success_total 26879
telemt_upstream_connect_fail_total 178
telemt_upstream_connect_attempts_per_request{bucket="1"} 27057
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14887
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11873
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 119
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 178
telemt_me_keepalive_timeout_total 5630
telemt_me_reconnect_attempts_total 28281
telemt_me_reconnect_success_total 18176
telemt_me_reader_eof_total 19527
telemt_me_idle_close_by_peer_total 19526
telemt_me_route_drop_no_conn_total 1505347
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3699244
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 14487
telemt_desync_full_logged_total 3837
telemt_desync_suppressed_total 10650
telemt_desync_frames_bucket_total{bucket="1_2"} 3606
telemt_desync_frames_bucket_total{bucket="3_10"} 5496
telemt_desync_frames_bucket_total{bucket="gt_10"} 5385
telemt_pool_swap_total 107
telemt_me_writer_removed_unexpected_total 18744
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 18163
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 568
telemt_user_connections_total{user="hello"} 3701413
telemt_user_connections_current{user="hello"} 1817
telemt_user_octets_from_client{user="hello"} 52265031444 (48.68 GB)
telemt_user_octets_to_client{user="hello"} 1153269289129 (1.05 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 461
telemt_user_unique_ips_recent_window{user="hello"} 224
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 26831.7 (7h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 401029
telemt_connections_bad_total 29587
telemt_handshake_timeouts_total 10337
telemt_upstream_connect_attempt_total 7771
telemt_upstream_connect_success_total 7597
telemt_upstream_connect_fail_total 174
telemt_upstream_connect_attempts_per_request{bucket="1"} 7771
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4372
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3094
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 18
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 113
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 174
telemt_me_keepalive_timeout_total 1580
telemt_me_reconnect_attempts_total 8211
telemt_me_reconnect_success_total 4816
telemt_me_reader_eof_total 5101
telemt_me_idle_close_by_peer_total 5100
telemt_me_route_drop_no_conn_total 152652
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 349668
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1238
telemt_desync_full_logged_total 314
telemt_desync_suppressed_total 924
telemt_desync_frames_bucket_total{bucket="1_2"} 239
telemt_desync_frames_bucket_total{bucket="3_10"} 591
telemt_desync_frames_bucket_total{bucket="gt_10"} 408
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 4981
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 4808
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 165
telemt_user_connections_total{user="hello"} 351006
telemt_user_connections_current{user="hello"} 540
telemt_user_octets_from_client{user="hello"} 3540119339 (3.30 GB)
telemt_user_octets_to_client{user="hello"} 101873859336 (94.88 GB)
telemt_user_msgs_from_client{user="hello"} 4402
telemt_user_msgs_to_client{user="hello"} 9145
telemt_user_unique_ips_current{user="hello"} 163
telemt_user_unique_ips_recent_window{user="hello"} 91
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 156788.4 (43h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2963979
telemt_connections_bad_total 28448
telemt_handshake_timeouts_total 198040
telemt_upstream_connect_attempt_total 35014
telemt_upstream_connect_success_total 35003
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 35013
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18101
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16768
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 129
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 3382
telemt_me_reconnect_attempts_total 29408
telemt_me_reconnect_success_total 26853
telemt_me_reader_eof_total 28472
telemt_me_idle_close_by_peer_total 28471
telemt_me_route_drop_no_conn_total 1008618
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2446282
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8489
telemt_desync_full_logged_total 2809
telemt_desync_suppressed_total 5680
telemt_desync_frames_bucket_total{bucket="1_2"} 1363
telemt_desync_frames_bucket_total{bucket="3_10"} 3109
telemt_desync_frames_bucket_total{bucket="gt_10"} 4017
telemt_pool_swap_total 147
telemt_me_writer_removed_unexpected_total 27168
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 26812
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 315
telemt_user_connections_total{user="hello"} 2445646
telemt_user_connections_current{user="hello"} 1157
telemt_user_octets_from_client{user="hello"} 40234703152 (37.47 GB)
telemt_user_octets_to_client{user="hello"} 854353321473 (795.68 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 301
telemt_user_unique_ips_recent_window{user="hello"} 150
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 156788.8 (43h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1914766
telemt_connections_bad_total 18234
telemt_handshake_timeouts_total 178267
telemt_upstream_connect_attempt_total 48926
telemt_upstream_connect_success_total 46588
telemt_upstream_connect_fail_total 2201
telemt_upstream_connect_attempts_per_request{bucket="1"} 48652
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27882
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18615
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2200
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 11947
telemt_me_reconnect_attempts_total 41894
telemt_me_reconnect_success_total 32911
telemt_me_reader_eof_total 35343
telemt_me_idle_close_by_peer_total 35336
telemt_me_route_drop_no_conn_total 678641
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1576538
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3117
telemt_desync_full_logged_total 1012
telemt_desync_suppressed_total 2105
telemt_desync_frames_bucket_total{bucket="1_2"} 862
telemt_desync_frames_bucket_total{bucket="3_10"} 1283
telemt_desync_frames_bucket_total{bucket="gt_10"} 972
telemt_pool_swap_total 136
telemt_me_writer_removed_unexpected_total 33455
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 32887
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 544
telemt_user_connections_total{user="hello"} 1581229
telemt_user_connections_current{user="hello"} 641
telemt_user_octets_from_client{user="hello"} 24391567941 (22.72 GB)
telemt_user_octets_to_client{user="hello"} 599645785094 (558.46 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 188
telemt_user_unique_ips_recent_window{user="hello"} 97
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 26224.6 (7h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 428969
telemt_connections_bad_total 4485
telemt_handshake_timeouts_total 4362
telemt_upstream_connect_attempt_total 5957
telemt_upstream_connect_success_total 5762
telemt_upstream_connect_fail_total 195
telemt_upstream_connect_attempts_per_request{bucket="1"} 5957
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2666
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3091
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 195
telemt_me_keepalive_timeout_total 845
telemt_me_reconnect_attempts_total 16125
telemt_me_reconnect_success_total 4414
telemt_me_reader_eof_total 4874
telemt_me_idle_close_by_peer_total 4874
telemt_me_route_drop_no_conn_total 165929
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 400936
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1261
telemt_desync_full_logged_total 401
telemt_desync_suppressed_total 860
telemt_desync_frames_bucket_total{bucket="1_2"} 412
telemt_desync_frames_bucket_total{bucket="3_10"} 504
telemt_desync_frames_bucket_total{bucket="gt_10"} 345
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 4814
telemt_me_refill_failed_total 364
telemt_me_writer_restored_same_endpoint_total 4410
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 400
telemt_user_connections_total{user="hello"} 400912
telemt_user_connections_current{user="hello"} 923
telemt_user_octets_from_client{user="hello"} 4578222800 (4.26 GB)
telemt_user_octets_to_client{user="hello"} 126509881292 (117.82 GB)
telemt_user_unique_ips_current{user="hello"} 223
telemt_user_unique_ips_recent_window{user="hello"} 113
```