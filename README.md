# Server Metrics 2026-03-13 17:38:30 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 128392.0 (35h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4095384
telemt_connections_bad_total 37525
telemt_handshake_timeouts_total 101185
telemt_upstream_connect_attempt_total 27234
telemt_upstream_connect_success_total 27056
telemt_upstream_connect_fail_total 178
telemt_upstream_connect_attempts_per_request{bucket="1"} 27234
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14967
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11968
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 121
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 178
telemt_me_keepalive_timeout_total 5684
telemt_me_reconnect_attempts_total 28415
telemt_me_reconnect_success_total 18309
telemt_me_reader_eof_total 19671
telemt_me_idle_close_by_peer_total 19670
telemt_me_route_drop_no_conn_total 1522857
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3740300
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 14650
telemt_desync_full_logged_total 3893
telemt_desync_suppressed_total 10757
telemt_desync_frames_bucket_total{bucket="1_2"} 3639
telemt_desync_frames_bucket_total{bucket="3_10"} 5560
telemt_desync_frames_bucket_total{bucket="gt_10"} 5451
telemt_pool_swap_total 108
telemt_me_writer_removed_unexpected_total 18881
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 18296
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 572
telemt_user_connections_total{user="hello"} 3742469
telemt_user_connections_current{user="hello"} 1487
telemt_user_octets_from_client{user="hello"} 52742733312 (49.12 GB)
telemt_user_octets_to_client{user="hello"} 1163474209061 (1.06 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 429
telemt_user_unique_ips_recent_window{user="hello"} 198
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 28055.9 (7h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 419119
telemt_connections_bad_total 31507
telemt_handshake_timeouts_total 10424
telemt_upstream_connect_attempt_total 8039
telemt_upstream_connect_success_total 7865
telemt_upstream_connect_fail_total 174
telemt_upstream_connect_attempts_per_request{bucket="1"} 8039
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4525
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3204
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 18
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 118
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 174
telemt_me_keepalive_timeout_total 1598
telemt_me_reconnect_attempts_total 8391
telemt_me_reconnect_success_total 4995
telemt_me_reader_eof_total 5291
telemt_me_idle_close_by_peer_total 5290
telemt_me_route_drop_no_conn_total 158495
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 365334
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1265
telemt_desync_full_logged_total 322
telemt_desync_suppressed_total 943
telemt_desync_frames_bucket_total{bucket="1_2"} 244
telemt_desync_frames_bucket_total{bucket="3_10"} 598
telemt_desync_frames_bucket_total{bucket="gt_10"} 423
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 5166
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 4987
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 171
telemt_user_connections_total{user="hello"} 366672
telemt_user_connections_current{user="hello"} 580
telemt_user_octets_from_client{user="hello"} 3767329123 (3.51 GB)
telemt_user_octets_to_client{user="hello"} 110169103444 (102.60 GB)
telemt_user_msgs_from_client{user="hello"} 4402
telemt_user_msgs_to_client{user="hello"} 9145
telemt_user_unique_ips_current{user="hello"} 163
telemt_user_unique_ips_recent_window{user="hello"} 89
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 158012.7 (43h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2995358
telemt_connections_bad_total 28475
telemt_handshake_timeouts_total 200628
telemt_upstream_connect_attempt_total 35292
telemt_upstream_connect_success_total 35282
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 35292
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18239
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16908
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 130
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 3422
telemt_me_reconnect_attempts_total 29641
telemt_me_reconnect_success_total 27087
telemt_me_reader_eof_total 28718
telemt_me_idle_close_by_peer_total 28717
telemt_me_route_drop_no_conn_total 1020676
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2473981
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8508
telemt_desync_full_logged_total 2819
telemt_desync_suppressed_total 5689
telemt_desync_frames_bucket_total{bucket="1_2"} 1366
telemt_desync_frames_bucket_total{bucket="3_10"} 3116
telemt_desync_frames_bucket_total{bucket="gt_10"} 4026
telemt_pool_swap_total 148
telemt_me_writer_removed_unexpected_total 27402
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 27046
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 315
telemt_user_connections_total{user="hello"} 2473337
telemt_user_connections_current{user="hello"} 1167
telemt_user_octets_from_client{user="hello"} 40648835504 (37.86 GB)
telemt_user_octets_to_client{user="hello"} 862868175581 (803.61 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 309
telemt_user_unique_ips_recent_window{user="hello"} 158
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 158013.1 (43h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1930971
telemt_connections_bad_total 18256
telemt_handshake_timeouts_total 178588
telemt_upstream_connect_attempt_total 49153
telemt_upstream_connect_success_total 46814
telemt_upstream_connect_fail_total 2202
telemt_upstream_connect_attempts_per_request{bucket="1"} 48879
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28001
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18722
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2201
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 11970
telemt_me_reconnect_attempts_total 42077
telemt_me_reconnect_success_total 33094
telemt_me_reader_eof_total 35540
telemt_me_idle_close_by_peer_total 35533
telemt_me_route_drop_no_conn_total 685310
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1591959
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3120
telemt_desync_full_logged_total 1014
telemt_desync_suppressed_total 2106
telemt_desync_frames_bucket_total{bucket="1_2"} 865
telemt_desync_frames_bucket_total{bucket="3_10"} 1283
telemt_desync_frames_bucket_total{bucket="gt_10"} 972
telemt_pool_swap_total 137
telemt_me_writer_removed_unexpected_total 33639
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 33070
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 545
telemt_user_connections_total{user="hello"} 1596650
telemt_user_connections_current{user="hello"} 630
telemt_user_octets_from_client{user="hello"} 24590142801 (22.90 GB)
telemt_user_octets_to_client{user="hello"} 604044194434 (562.56 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 178
telemt_user_unique_ips_recent_window{user="hello"} 103
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 27448.9 (7h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 449624
telemt_connections_bad_total 4557
telemt_handshake_timeouts_total 4759
telemt_upstream_connect_attempt_total 6322
telemt_upstream_connect_success_total 6118
telemt_upstream_connect_fail_total 204
telemt_upstream_connect_attempts_per_request{bucket="1"} 6322
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2853
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3258
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 204
telemt_me_keepalive_timeout_total 869
telemt_me_reconnect_attempts_total 17579
telemt_me_reconnect_success_total 4716
telemt_me_reader_eof_total 5211
telemt_me_idle_close_by_peer_total 5211
telemt_me_route_drop_no_conn_total 172953
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 420133
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1279
telemt_desync_full_logged_total 410
telemt_desync_suppressed_total 869
telemt_desync_frames_bucket_total{bucket="1_2"} 416
telemt_desync_frames_bucket_total{bucket="3_10"} 511
telemt_desync_frames_bucket_total{bucket="gt_10"} 352
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 5154
telemt_me_refill_failed_total 400
telemt_me_writer_restored_same_endpoint_total 4712
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 438
telemt_user_connections_total{user="hello"} 420106
telemt_user_connections_current{user="hello"} 828
telemt_user_octets_from_client{user="hello"} 4792204396 (4.46 GB)
telemt_user_octets_to_client{user="hello"} 131537932304 (122.50 GB)
telemt_user_unique_ips_current{user="hello"} 198
telemt_user_unique_ips_recent_window{user="hello"} 91
```