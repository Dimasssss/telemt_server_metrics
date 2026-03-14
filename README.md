# Server Metrics 2026-03-14 09:49:34 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 186654.3 (51h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5331018
telemt_connections_bad_total 50842
telemt_handshake_timeouts_total 119171
telemt_upstream_connect_attempt_total 39154
telemt_upstream_connect_success_total 38899
telemt_upstream_connect_fail_total 255
telemt_upstream_connect_attempts_per_request{bucket="1"} 39154
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21093
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17652
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 154
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 255
telemt_me_keepalive_timeout_total 7536
telemt_me_reconnect_attempts_total 38495
telemt_me_reconnect_success_total 27279
telemt_me_reader_eof_total 29265
telemt_me_idle_close_by_peer_total 29264
telemt_me_route_drop_no_conn_total 2015261
telemt_me_route_drop_channel_closed_total 29
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4885826
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 18705
telemt_desync_full_logged_total 5107
telemt_desync_suppressed_total 13598
telemt_desync_frames_bucket_total{bucket="1_2"} 4591
telemt_desync_frames_bucket_total{bucket="3_10"} 7141
telemt_desync_frames_bucket_total{bucket="gt_10"} 6973
telemt_pool_swap_total 161
telemt_me_writer_removed_unexpected_total 28030
telemt_me_refill_failed_total 345
telemt_me_writer_restored_same_endpoint_total 27266
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 751
telemt_user_connections_total{user="hello"} 4887295
telemt_user_connections_current{user="hello"} 1618
telemt_user_octets_from_client{user="hello"} 74833527304 (69.69 GB)
telemt_user_octets_to_client{user="hello"} 1560141652853 (1.42 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 449
telemt_user_unique_ips_recent_window{user="hello"} 243
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 86318.1 (23h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 967072
telemt_connections_bad_total 55625
telemt_handshake_timeouts_total 20339
telemt_upstream_connect_attempt_total 22751
telemt_upstream_connect_success_total 22462
telemt_upstream_connect_fail_total 289
telemt_upstream_connect_attempts_per_request{bucket="1"} 22751
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12203
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9969
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 41
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 249
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 289
telemt_me_keepalive_timeout_total 2226
telemt_me_reconnect_attempts_total 26022
telemt_me_reconnect_success_total 16150
telemt_me_reader_eof_total 17319
telemt_me_idle_close_by_peer_total 17318
telemt_me_route_drop_no_conn_total 323358
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 787976
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2206
telemt_desync_full_logged_total 693
telemt_desync_suppressed_total 1513
telemt_desync_frames_bucket_total{bucket="1_2"} 501
telemt_desync_frames_bucket_total{bucket="3_10"} 945
telemt_desync_frames_bucket_total{bucket="gt_10"} 760
telemt_pool_swap_total 71
telemt_me_writer_removed_unexpected_total 16688
telemt_me_refill_failed_total 302
telemt_me_writer_restored_same_endpoint_total 16142
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 538
telemt_user_connections_total{user="hello"} 789872
telemt_user_connections_current{user="hello"} 642
telemt_user_octets_from_client{user="hello"} 8595876297 (8.01 GB)
telemt_user_octets_to_client{user="hello"} 272318569988 (253.62 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 200
telemt_user_unique_ips_recent_window{user="hello"} 108
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 216274.8 (60h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3795018
telemt_connections_bad_total 44549
telemt_handshake_timeouts_total 250922
telemt_upstream_connect_attempt_total 48810
telemt_upstream_connect_success_total 48789
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 48810
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25771
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22763
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 248
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10909
telemt_me_reconnect_attempts_total 42697
telemt_me_reconnect_success_total 37701
telemt_me_reader_eof_total 40034
telemt_me_idle_close_by_peer_total 40033
telemt_me_route_drop_no_conn_total 1303935
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3170744
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10233
telemt_desync_full_logged_total 3478
telemt_desync_suppressed_total 6755
telemt_desync_frames_bucket_total{bucket="1_2"} 1841
telemt_desync_frames_bucket_total{bucket="3_10"} 3708
telemt_desync_frames_bucket_total{bucket="gt_10"} 4684
telemt_pool_swap_total 203
telemt_pool_stale_pick_total 3
telemt_me_writer_removed_unexpected_total 38224
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 37660
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 523
telemt_user_connections_total{user="hello"} 3169913
telemt_user_connections_current{user="hello"} 859
telemt_user_octets_from_client{user="hello"} 53554807712 (49.88 GB)
telemt_user_octets_to_client{user="hello"} 1136460039149 (1.03 TB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 269
telemt_user_unique_ips_recent_window{user="hello"} 151
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 216277.5 (60h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2508142
telemt_connections_bad_total 23396
telemt_handshake_timeouts_total 314749
telemt_upstream_connect_attempt_total 66921
telemt_upstream_connect_success_total 64419
telemt_upstream_connect_fail_total 2365
telemt_upstream_connect_attempts_per_request{bucket="1"} 66647
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38454
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25799
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2364
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20645
telemt_me_reconnect_attempts_total 58274
telemt_me_reconnect_success_total 46622
telemt_me_reader_eof_total 49980
telemt_me_idle_close_by_peer_total 49973
telemt_me_route_drop_no_conn_total 839154
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1965802
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4032
telemt_desync_full_logged_total 1319
telemt_desync_suppressed_total 2713
telemt_desync_frames_bucket_total{bucket="1_2"} 1137
telemt_desync_frames_bucket_total{bucket="3_10"} 1646
telemt_desync_frames_bucket_total{bucket="gt_10"} 1249
telemt_pool_swap_total 188
telemt_me_writer_removed_unexpected_total 47389
telemt_me_refill_failed_total 355
telemt_me_writer_restored_same_endpoint_total 46598
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 767
telemt_user_connections_total{user="hello"} 1971980
telemt_user_connections_current{user="hello"} 488
telemt_user_octets_from_client{user="hello"} 29463737631 (27.44 GB)
telemt_user_octets_to_client{user="hello"} 712867616294 (663.91 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 141
telemt_user_unique_ips_recent_window{user="hello"} 73
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 85710.9 (23h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 951877
telemt_connections_bad_total 14620
telemt_handshake_timeouts_total 12433
telemt_upstream_connect_attempt_total 21714
telemt_upstream_connect_success_total 21129
telemt_upstream_connect_fail_total 585
telemt_upstream_connect_attempts_per_request{bucket="1"} 21714
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10083
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11020
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 585
telemt_me_keepalive_timeout_total 1682
telemt_me_reconnect_attempts_total 70771
telemt_me_reconnect_success_total 16839
telemt_me_reader_eof_total 18934
telemt_me_idle_close_by_peer_total 18933
telemt_me_route_drop_no_conn_total 363983
telemt_me_route_drop_channel_closed_total 16
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 882566
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2324
telemt_desync_full_logged_total 727
telemt_desync_suppressed_total 1597
telemt_desync_frames_bucket_total{bucket="1_2"} 772
telemt_desync_frames_bucket_total{bucket="3_10"} 872
telemt_desync_frames_bucket_total{bucket="gt_10"} 680
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 18680
telemt_me_refill_failed_total 1680
telemt_me_writer_restored_same_endpoint_total 16834
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1841
telemt_user_connections_total{user="hello"} 882510
telemt_user_connections_current{user="hello"} 725
telemt_user_octets_from_client{user="hello"} 15662487908 (14.59 GB)
telemt_user_octets_to_client{user="hello"} 296018896912 (275.69 GB)
telemt_user_unique_ips_current{user="hello"} 189
telemt_user_unique_ips_recent_window{user="hello"} 103
```